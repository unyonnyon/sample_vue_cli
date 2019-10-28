<template>
    <div class="container">
        <div class="row">
            <div class="col-4 orange">
                <p>{{data.a}}</p>
            </div>
            <div class="col-4 orangered">
                <p>{{data.b}}</p>
            </div>
            <div class="col-4 green">
                <p>{{data.c}}</p>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    props: {
        data: {
            type: Object
        }
    },
    data: function() {
        return { myname: "" };
    },
    mounted: function() {
        console.log("mounted!!");
    },
    created: function() {
        console.log("created!!");
    }
};
</script>

<style>
.orange {
    background: orange;
}
.orangered {
    background: orangered;
}
.green {
    background: green;
}
.skyblue {
    background: skyblue;
}
</style>