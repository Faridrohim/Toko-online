<template>

<footer >
    <div class="container">
            <div class="logo">
                <img src="@/assets/svg/logo.svg" alt="Logo" class="logo">
            </div>
        <div class="col-2">
            <div class="Halaman">
                <h6 style="font-size: 18px;">Halaman</h6>
                <div class="Link-Halaman">
                    <a href="#">
                        <p>Pria</p>
                    </a>
                    <a href="#">
                        <p>Wanita</p>
                    </a>
                    <a href="#">
                        <p>Tentang Kami</p>
                    </a>
                    <a href="#">
                        <p>Blog</p>
                    </a>
                </div>
            </div>
        </div>
        <div class="col-2">
            <div class="Bantuan">
                <h6 style="font-size: 18px;">Bantuan dan Panduan</h6>
                <div class="Link-Bantuan">
                    <a href="#">
                        <p>Syarat dan ketentuan</p>
                    </a>
                    <a href="#">
                        <p>Kebijakan Privasi</p>
                    </a>
                    <a href="#">
                        <p>Tentang Kami</p>
                    </a>
                </div>
            </div>            
        </div>
        <div class="col-2">
            <div class="kontak">
                <h6 style="font-size: 18px;">Kontak Kami</h6>
                <div class="Link-Kontak">
                    <a href="#">
                        <div class="telpon">
                            <img src="@/assets/svg/telpon.svg" alt="Logo" class="icon-telpon">
                            <span class="span-telpon ">(+62) 889-019-8920</span>
                            <br>
                        </div>
                    </a>
                    <a href="#">
                        <div class="mail">
                            <img src="@/assets/svg/mail.svg" alt="Logo" class="icon-mail">
                            <span class="span-mail ">@anonym@gmail.com</span>
                        </div>
                    </a>
                    <a href="#">
                    </a>
                </div>
            </div>
        </div>
        <div class="col-2">
            <div class="Social">
                <h6 style="font-size: 18px;">Social Media</h6>
                <img src="@/assets/svg/facebook.svg" alt="Logo" class="icon-social">
                <img src="@/assets/svg/instagram.svg" alt="Logo" class="icon-social">
                <img src="@/assets/svg/twitter.svg" alt="Logo" class="icon-social">
                <img src="@/assets/svg/youtube.svg" alt="Logo" class="icon-social">
                <img src="@/assets/img/wordpres.png" alt="Logo" class="icon-word">
            </div>
        </div>
        <p class="copyright">@ 2023. Online Store. All rights reserved.</p>
    </div>
    <div class="border-bottom"></div>
</footer>

</template>

<script setup>

</script>

<style scoped>
    @media screen and (max-width: 414px) {
    .container {
        width: 100%;
        height: auto;
        background-color: #232121;
        position: relative;
        font-family: 'inter';
        margin-top: 0;
        padding: 20px;
    }

    .border-bottom {
        height: 1px;
        width: 90%;
        border-bottom: 1px #FFFFFF50 solid;
        margin-left: 5%;
        position: relative;
        margin-top: 20px;
    }

    .logo {
        width: 80px;
        height: auto;
        position: relative;
        margin-left: 10px;
        margin-top: 10px;
    }

    .copyright {
        margin-left: 20px;
        color: #FFFFFF;
        font-size: 10px;
        margin-top: 20px;
    }

    .icon-telpon {
        margin-top: 10px;
        height: 20px;
        width: auto;
    }

    .icon-mail {
        margin-top: 10px;
        width: 20px;
    }

    .icon-social {
        margin-top: 20px;
        height: 16px;
        width: auto;
        margin-right: 10px;
    }

    .icon-word {
        height: 30px;
        margin-bottom: -5px;
    }

    .Halaman, .Bantuan, .kontak, .Social {
        color: #FFFFFF;
        margin-top: 10px;
    }

    .Halaman {
        margin-left: 5%;
        margin-top: 20px;
    }

    .Bantuan {
        margin-left: 20%;
        margin-top: -50px;
    }

    .kontak {
        margin-left: 40%;
        margin-top: -30px;
    }

    .Social {
        margin-left: 60%;
        margin-top: -20px;
    }

    .Halaman a, .Bantuan a, .kontak a, .Social a {
        text-decoration: none;
        color: #FFFFFF;
        font-size: 12px;
    }

    .Link-Halaman p, .Link-Bantuan p {
        margin-top: 5px;
        font-weight: 400;
        font-size: 12px;
    }

    .span-telpon {
        position: relative;
        margin-top: 10px;
        margin-left: 5px;
        font-size: 12px;
    }

    .span-mail {
        position: relative;
        margin-top: 10px;
        margin-left: 5px;
        font-size: 12px;
    }
}

.container {
    width:  1220px;
    height: 400px;
    background-color: #232121;
    position: absolute;
    bottom: 0;
    font-family: 'inter';
    margin-top: 750px
    }
.border-bottom {
    height: 275px;
    width: 78.5%;
    border-bottom:  1px #FFFFFF50 solid;
    margin-left: 10.5%;
    position: absolute;
    margin-top: 800px;
}
.logo {
    width: 100px; 
    height: auto;
    position: absolute;
    margin-left: 40px;
    margin-top: 35px;
    }
.copyright {
    margin-left: 80px;
    color: #FFFFFF;
    font-size: 12px;
    margin-top: 9%;

}

.icon-telpon {
    margin-top: 10px;
    height: 23px;
    width: auto;
}
.icon-mail {
    margin-top: 13px;
    width: 23px;
}

.icon-social {
    margin-top: 25px;
    height: 19px;
    width: auto;
    margin-right: 20px;
}
.icon-word{
    height: 35px;
    margin-bottom: -7px;
}

.Halaman, .Bantuan, .kontak, .Social {
    color: #FFFFFF;
}
.Halaman {
    margin-left: 18%;
    margin-top: 70px;
}
.Bantuan {
    margin-left: 32%;
    margin-top: -128px;
}
.kontak{
    margin-left: 54%;
    margin-top: -102px;
}
.Social{
    margin-left: 72%;
    margin-top: -93px;
}

.Halaman a,.Bantuan a, .kontak a,.Social a {
    text-decoration: none;
    color: #FFFFFF;
}
.Link-Halaman p, .Link-Bantuan p {
    margin-top: 10px;
    font-weight: 400;
    font-size: 14px;
}

.span-telpon{
    position: absolute;
    margin-top: 11px;
    margin-left: 6px;
    font-size: 14px;
    
}
.span-mail {
    position: absolute;
    margin-top: 13px;
    margin-left: 6px;
    font-size: 14px;

}


    
</style>
