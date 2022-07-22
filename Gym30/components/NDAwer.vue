<template>

    <div class="sidebar">
        <link href='https://unpkg.com/boxicons@2.1.2/css/boxicons.min.css' rel='stylesheet'>
        
        <ul class="nav-links">
            <li>
                <img class="lg" src="/logo2.png" width="200">
            </li>
            <br />
            <br />
            <li>
                <img class="lg" src="/admin.png" width="200">
            </li><br />
            <br /><br />
            <br />
            <li>
                <a href="homeSA">
                    <i class='bx bxs-home-alt-2'></i>
                    <span class="link_name">Home</span>
                </a>
            </li>
            <li>
                <a href="Membership">
                    <i class='bx bxs-credit-card' ></i>
                    <span class="link_name">Membership</span>
                </a>
            </li>
            <li>
                <a href="Classes">
                    <i class='bx bx-dumbbell' ></i>
                    <span class="link_name">Admin</span>
                </a>
            </li>
            <br /><br /><br /><br />
            <br /><br />
            <br /><br />
            <br /><br />
            <br /><br />
            <br /><br />
            <br /><br />
            <br /><br />
            <br />
            <li>
                <a href="/">
                    <i class='bx bx-log-out' ></i>
                    <span class="link_name">Log out</span>
                </a>
            </li>
        </ul>
    </div>
</template>

<script>
export default {

}
</script>

<style>
.lg {
    margin: 75px 0px 30px 0px;
}
.sidebar{
    position: fixed;
    height: 100%;
    width: 240px;
    background: #1a2e39;
}
.sidebar .nav-links li{
    height: 50px;
    width: 100%;
    list-style: none;
}
.sidebar .nav-links li a{
    height: 100%;
    width: 100%;
    color: #afafaf;
    display: flex;
    align-items: center;
    text-decoration: none;

}
.sidebar .nav-links li a:hover{
    background: #4fbdba;
    color: #ffff;

}
.sidebar .nav-links li a i{
    min-width: 60px;
    text-align: center;
    font-size: 18px;
    color: #afafaf;
}
</style>