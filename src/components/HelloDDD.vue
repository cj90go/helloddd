<template>
    <div class="container">
        <h3>{{msg}}</h3>
        <ul id="myTab" class="nav nav-tabs">
            <li class="active">
                <a href="#zero" data-toggle="tab">
                    实体
                </a>
            </li>
            <li>
                <a href="#first" data-toggle="tab">语文</a>
            </li>
            <li>
                <a href="#second" data-toggle="dropdown">数学
                    <b class="caret"></b></a>

                <ul class="dropdown-menu">
                    <li><a href="#s_1" tabindex="-1" data-toggle="tab">高数</a></li>
                    <li><a href="#s_2" tabindex="-1" data-toggle="tab">小数</a></li>
                </ul>
            </li>
        </ul>
        <div id="myTabContent" class="tab-content">
            <div class="tab-pane active" id="zero">
                <p> There is a good programer</p>
            </div>
            <div class="tab-pane fade" id="first">
                <p>学海无涯</p>
            </div>
            <div class="tab-pane fade" id="s_1">
                <p>书山有路</p>
            </div>
            <div class="tab-pane fade" id="s_2">
                <p>智勇双枪</p>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "HelloDDD",
        props: {
            msg: String
        }
    }
</script>

<style scoped>

</style>