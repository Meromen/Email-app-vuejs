<template>
    <aside class="sm-side">
        <div class="user-head">
            <img src="src/assets/images/profile.jpg"/>

            <div class="user-name">
                <h5>Yuri Pysin</h5>
                <span class="email-address">urabbbc@yandex.ru</span>
            </div>
        </div>

        <ul class="inbox-nav">
            <li class="active">
                <a href="#">
                    <i class="fa fa-inbox"></i>Inbox <span class="label label-danger pull-right">?</span>
                </a>
            </li>

            <li class="active">
                <a href="#">
                    <i class="fa fa-envelope"></i>Sent <span class="label label-danger pull-right">?</span>
                </a>
            </li>

            <li class="active">
                <a href="#">
                    <i class="fa fa-bookmark-o"></i>Important <span class="label label-danger pull-right">?</span>
                </a>
            </li>

            <li class="active">
                <a href="#">
                    <i class="fa fa-trash-o"></i>Trash <span class="label label-danger pull-right">?</span>
                </a>
            </li>
        </ul>
    </aside>
</template>

<script>
    export default {

    }
</script>