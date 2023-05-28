<template>
    <div class="grid grid-cols-2 gap-8">
        <div>
            <input type="text" class="border-2 w-full border-gray-500" v-model="username">
            <input type="file" @change="onFileChange">
        </div>
        <div>
            <div>{{username}}</div>
            <img :src="image" alt="">
        </div>
    </div>
</template>

<<script>
export default {
    name:"post",
    data() {
        return {
            username:'',
            image:'',
        }
    },
    methods: {
        onFileChange(e) {
            var files = e.target.files || e.dataTransfer.files;
            if (!files.length)
                return;
            this.createImage(files[0]);
        },
        createImage(file) {
            var image = new Image();
            var reader = new FileReader();
            var vm = this;

            reader.onload = (e) => {
                vm.image = e.target.result;
            };
            reader.readAsDataURL(file);
        },
        removeImage: function (e) {
            this.image = '';
        }
    },
}
</script>