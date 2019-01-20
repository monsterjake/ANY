html {
    position: relative;
    min-height: 100%;
}

body {
    width: 100%;
    height: 100%;
    min-width: 1000px;
    background-repeat: no-repeat;
    background-position: center top;
    /*margin-bottom: 155px;*/
}

.ellipsis {
    text-overflow: ellipsis;
    white-space: nowrap;
    overflow: hidden;
}

.container {
    width: 1000px;
    max-width: none !important;
    padding: 0;
}

.footer {
    position: absolute;
    bottom: 0;
    width: 100%;
    height: 155px;
}

    .footer .row {
        min-width: 1000px;
        background-color: #f2f2f2;
        height: 155px;
        margin: 0;
    }

        .footer .container {
            margin-top: 50px;
        }

            .footer .container > div:nth-child(2) {
                float: left;
                margin-left: 20px;
                padding-top: 10px;
            }


.carousel-indicators {
    position: absolute;
    bottom: 5px;
    z-index: 15;
    margin-left: 0;
    padding-left: 0;
    list-style: none;
    text-align: center;
    z-index: 100;
}

    .carousel-indicators li {
        margin: 0;
        background-color: #c6c8c8;
        border-color: #c6c8c8;
        transition: 250ms;
        margin-right: 15px;
        height: 17px;
        width: 17px;
    }

.enabled li {
    background-color: #c6c8c8;
    border-color: #c6c8c8;
    transition: 250ms;
    margin-right: 5px;
    height: 5px;
    width: 30px;
    border-radius: 0;
}

.carousel-indicators .active {
    margin: 0;
    width: 70px;
    height: 17px;
    background-color: #fe6128;
    border-color: #fe6128;
    margin-right: 15px;
}

.enabled .active {
    margin: 0;
    width: 30px;
    height: 5px;
    background-color: #fe6128;
    border-color: #fe6128;
    margin-right: 5px;
}

.defaultindicator {
    height: 5px;
    width: 25px;
    border-radius: 0;
}

    .defaultindicator > li:hover {
        background-color: #fe6128;
    }

#mainbanner {
    display: block !important;
}

    #mainbanner .carousel-inner {
        background-color: #000;
    }

        #mainbanner .carousel-inner .item img {
            max-width: none !important;
            width: 100%;
            display: block;
            line-height: 1;
            margin: 0 auto;
        }

        #mainbanner .carousel-inner .item > img:first-of-type {
            display: block;
        }

        #mainbanner .carousel-inner .item .butcontainer {
            width: 100%;
            height: auto;
            position: relative;
            z-index: 15;
        }

    #mainbanner .carousel-indicators {
        width: 501px;
        text-align: right;
    }

    #mainbanner .butcontainer .button {
        position: absolute;
        left: 60px;
        margin-left: 80px;
        bottom: 20px;
        z-index: 20;
    }


.column {
    margin-top: 60px;
    margin-bottom: 37px;
    margin-right: 24px;
    float: left;
    margin-left: 0;
}

    .column > img {
        margin-bottom: 15px;
    }

    .column:nth-child(3n+0) {
        margin-right: 0;
    }



.news {
    width: 316px;
    margin-bottom: 23px;
}

    .news .image {
        width: 316px;
        height: 140px;
    }

        .news .image > a img {
            border: 1px solid #c6c8c8;
            width: 314px;
            height: 138px;
            transition: 250ms;
	    display: block;
    	    margin: 0 auto;
        }

            .news .image > a img:hover {
                border: 1px solid #fe6128;
            }

    .news .title {
        font-size: 20px;
        color: #252525;
        margin-top: 10px;
        margin-left: 10px;
        margin-right: 10px;
    }

        .news .title a {
            text-decoration: none;
            transition: 250ms;
        }

            .news .title a:hover {
                color: #fe6128;
            }


.gamelist {
    width: 1000px;
    position: relative;
}

    .gamelist a > img.prev,
    .gamelist a > img.next{
        z-index: 20;
        position: absolute;
        top: 127px;
    }

    .gamelist .game {
        width: 316px /*!important*/;
        height: 325px;
        margin-right: 26px;
        float: left;
    }

        .gamelist .game:last-of-type {
            margin-right: 0 !important;
        }

        .gamelist .game .descbox {
            width: 316px;
            height: 325px;
            background-color: rgba(0,0,0, 0.9);
            padding-top: 30px;
            position: relative;
        }

    .gamelist .descbox .description {
        padding: 0 40px 0 40px;
    }

    .gamelist .description .title {
        font-size: 24px;
        margin-bottom: 25px;
        color: #fff;
    }

    .gamelist .description .text {
        font-size: 14px;
        color: #999999;
    }

    .gamelist .descbox .bottom {
        position: absolute;
        bottom: 0px;
        left: 0px;
        border-top: 1px solid #3b3e44;
    }

        .gamelist .descbox .bottom > div {
            float: left;
            width: 158px;
        }

        .gamelist .descbox .bottom img {
            display: block;
            margin: 15px auto 15px auto;
        }

.slick-list {
    margin: 0 -12px;
}

.slick-slide {
    margin: 0 12px;
}

/*Modal Vertical Align Center*/
.vertical-alignment-helper {
    display: table;
    height: 100%;
    width: 100%;
    pointer-events: none;
}

.vertical-align-center {
    display: table-cell;
    vertical-align: middle;
    pointer-events: none;
}

#video .modal-content {
    width: 560px;
    height: 315px;
    margin: 0 auto;
    pointer-events: all;
}

.modal-open {
    padding-right: 0px !important;
}
/* End of Modal Vertical Align Center */

/* Promo Modal */
.promo-modal .modal-content {
    width: 400px; /*inherit*/
    height: 400px; /*inherit*/
    margin: 0 auto;
    pointer-events: all;
    background-color: #fff;
    display: table;
    overflow-y: auto;
    overflow-x: auto;
    width: auto;
    border-radius: 0;
}

    .promo-modal .modal-content .modal-header {
        border-bottom: none;
        padding: 20px 20px 0 20px;
        position: relative;
    }

        .modal-content .modal-header > img {
            width: 170px;
        }


    .promo-modal .modal-content .modal-body {
        padding: 20px 20px 25px 20px;
    }

        .modal-content .modal-body .promo-content {
            height: 100%;
            width: 100%;
            padding: 20px;
            border: 1px solid #4e4d4d;
        }

.modal-footer {
    border-top: none !important;
    width: 100%;
}
/* End of Promo Modal */

.showvid {
    cursor: pointer;
}

.playvid > img {
    position: absolute;
    top: 85px;
    left: 70px;
}


.featured {
    width: 1000px;
    margin: 0 auto;
}

    .featured .content {
        width: 207px;
        height: 277px;
        background-color: #000;
        margin-right: 16px;
        float: left;
    }

        .featured .content:nth-child(3) {
            margin-right: 24px;
        }

        .featured .content .title {
            height: 64px;
            background-color: #161616;
            color: #999;
            font-weight: bold;
            line-height: 1.2;
            padding: 17px 10px 17px 10px;
        }

        .featured .content > a {
            text-decoration: none;
        }

        .featured .content .title:hover {
            color: #fff;
            transition: 200ms;
        }

        .featured .content .image {
            transition: 200ms;
        }

    .featured .featuredbox .image {
        opacity: .8;
    }

    .featured .fbbox {
        width: 317px;
        height: 277px;
        float: left;
    }

.fbbox .title {
    background-color: #fff;
    height: 64px;
    color: #999;
    font-weight: bold;
}

    .fbbox .title span {
        display: inline-block;
        margin: 22px 30px 22px 10px;
    }

    .fbbox .title a {
        text-decoration: none;
    }

    .fbbox .title img {
        opacity: 0.9;
        transition: 200ms;
        margin-right: 5px;
    }

        .fbbox .title img:hover {
            opacity: 1;
        }




.form-group > label {
    font-weight: normal;
    font-family: Verdana;
    font-size: 18px;
    color: #b6b6b6;
}


.no-gutter {
    margin-left: 0;
    margin-right: 0;
}


.form-group .col-sm-5, .col-sm-6 {
    padding-left: 0;
    padding-right: 0;
}

.form-group .col-sm-3 {
    padding-left: 10px;
    padding-right: 0;
}









.gender.active {
    /*background: #f7941d;*/
}

.gender {
    width: 130px;
    padding: 10px;
    position: relative;
}

.gender-word {
    font-size: 15px;
    font-weight: 600;
    margin-left: 22px;
}

.radio-dot:before, .radio-dot:after {
    content: "";
    display: block;
    position: absolute;
    background: #fff;
    border-radius: 100%;
}

.radio-dot:before {
    width: 20px;
    height: 20px;
    border: 1px solid #ccc;
    top: 10px;
    left: 16px;
}

.radio-dot:after {
    width: 12px;
    height: 12px;
    border-radius: 100%;
    top: 14px;
    left: 20px;
}

.gender.active .gender-word, .gender-word {
    color: #b6b6b6;
}

.gender.active .radio-dot:after {
    background: #f7941d;
}

.gender.active .radio-dot:before {
    background: #fff;
    border-color: #699D17;
}

.gender:hover .radio-dot:before {
    border-color: #adadad;
}

.gender.active:hover .radio-dot:before {
    border-color: #699D17;
}


.gender.active .radio-dot:after {
    background: #f7941d;
}

.gender:hover .radio-dot:after {
    background: #e6e6e6;
}

.gender.active:hover .radio-dot:after {
    background: #f7941d;
}


.btn:active, .btn.active {
    -webkit-box-shadow: none;
    box-shadow: none;
}





.buttonspecial {
    background-color: #F8BB00;
    color: #ffffff;
    border: none;
    padding-top: 13px;
    padding-bottom: 13px;
    width: 315px;
    font-size: 26px;
    transition: 250ms;
}

    .buttonspecial:hover {
        background-color: #F7A31D;
    }

    .buttonspecial:focus {
        outline: 0;
    }


.buttongray {
    background-color: #777777;
    color: #fff;
        border: none;
    font-size: 16px;
    box-shadow: none;
    height: 26px;
    width: 149px;

    transition: 250ms;
}

    .buttongray:hover {
        color: #fff;
        background-color: #555555;
    }

    .buttongray:focus {
        outline: 0;
    }




.form-control-feedback {
    position: absolute;
    top: 0;
    right: 26px;
    z-index: 2;
    display: block;
    width: 26px;
    height: 26px;
    line-height: 25px;
    text-align: center;
    pointer-events: none;
}

.form-group label {
    color: #f2f2f2;
}

.body li {
    list-style: none;
}

    .body li:before {
        content: "•";
        vertical-align: middle;
        font-size: 50%;
        color: #847e80;
        padding-right: 6px;
    }

.body .has-error .form-control {
    border-color: #fe6128;
}

.has-error .form-control-feedback {
    color: #c75313;
    font-size: 17px;
    margin-right: -9px;
}

.body .help-block {
    margin-bottom: 0 !important;
    color: #fe6128;
}

.body .has-error .help-block,
.body #eula-error.help-block {
    color: #fe6128;
}

.gcform {
    width: 680px;
    background-color: #343232;
    margin: 0 auto;
}

    .gcform .head {
        height: 126px;
        border-bottom: 1px solid #4e4d4d;
        padding: 31px 40px 0 40px;
        color: #fff;
    }

    .gcform .body {
        padding: 31px 44px 50px 44px;
    }

.body .form-group input.form-control {
    height: 26px;
    width: 279px;
    margin-right: -6px;
    padding-bottom: 8px;
}

.body .form-group label {
    font-size: 14px;
}

.body #authenticate,
.body #refresh {
    margin-left: -8px;
}

.gcform .body .title {
    font-size: 18px;
    color: #10caf9;
    margin-bottom: 20px;
}

@media all and (-ms-high-contrast: none), (-ms-high-contrast: active) {
    /* IE10+ CSS styles go here */
    .body .form-group input.form-control,
    .searchbox input {
        height: 26px;
        width: 279px;
        margin-right: -6px;
        padding-bottom: 0px;
        padding-top: 0px;
    }
}

/* @media (max-width: 1000px) {
     #mainbanner .carousel-inner {
         height: 386px;
     }
 } */


.gom-sidenav {
    position: absolute;
    margin-top: 60px;
    left: 0;
    width: 65px;
    /* box-shadow: 5px 5px 15px #000; */
}

    .gom-sidenav a .button {
        width: 85px;
        position: relative;
        left: -20px;
        transition: 100ms;
    }

    .gom-sidenav a .button:hover {
        left: 0;
    }

        .gom-sidenav .button > img {
            display: block;
            margin: 0 0 0 20px;
            width: 65px;
            height: 65px;
        }

.gom-sidenav-scroll {
    position: fixed;
    top: 20px;
    left: 0;
    width: 65px;
    /* box-shadow: 5px 5px 15px #000; */
}

    .gom-sidenav-scroll a .button {
        width: 85px;
        position: relative;
        left: -20px;
        transition: 100ms;
    }

    .gom-sidenav-scroll a .button:hover {
        left: 0;
    }

        .gom-sidenav-scroll .button > img {
            display: block;
            margin: 0 0 0 20px;
            width: 65px;
            height: 65px;
        }
