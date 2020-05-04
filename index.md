<!doctype html>
<html>
<head>
<meta charset="utf-8">
<title>无标题文档</title>
</head>

<body bgcolor="#FB99DC">
<style>
    /*实现立体效果*/
    .img {
        width: 50px;
        height: 50px;
        margin: 0 auto;
        transform-style: preserve-3d;
        /*设置动画播放样式:动画对象 播放速度 时间 播放次数*/
        animation: rotate linear 20s infinite;
    }
    /*实现动画效果*/
    @-webkit-keyframes rotate {                /*sofari chrome*/
        from {
            transform: rotateX(0deg) rotateY(0deg);
        }
        to {
            transform: rotateX(360deg) rotateY(360deg);
        }
    }
    /*图片样式*/
    .pic{
        width: 200px;
        height: 200px;
        transform: rotateY(0deg) translateZ(100px);
    }
</style>
<div class="wrap">
    <!--部署内外层图片-->
    <div class="cube">
        <!--前面图片 -->
        <div class="out_front">
            <img src="https://timgsa.baidu.com/timg?image&amp;quality=80&amp;size=b9999_10000&amp;sec=1553678403567&amp;di=9de5989f2fa2efd6e80477ad19d995dc&amp;imgtype=0&amp;src=http%3A%2F%2Fattach.bbs.miui.com%2Fforum%2F201811%2F19%2F072123rjmrmsjnuv3msepw.jpeg" class="pic">
        </div>
        <!--后面图片 -->
        <div class="out_back">
            <img src="https://timgsa.baidu.com/timg?image&amp;quality=80&amp;size=b9999_10000&amp;sec=1553678403566&amp;di=48a1fd857ad0d132da2688392d22e437&amp;imgtype=0&amp;src=http%3A%2F%2Fi0.hdslb.com%2Fbfs%2Farticle%2Fa08ea9b71f481add983166f99c8552a74b8fe9d0.jpg" class="pic">
        </div>
        <!--左面图片 -->
        <div class="out_left">
            <img src="https://timgsa.baidu.com/timg?image&amp;quality=80&amp;size=b9999_10000&amp;sec=1553678403565&amp;di=aa0eecb27e2a362d3ed5a37fd54b0fdb&amp;imgtype=0&amp;src=http%3A%2F%2Fb-ssl.duitang.com%2Fuploads%2Fitem%2F201406%2F12%2F20140612203422_YWGYQ.jpeg" class="pic">
        </div>
        <!--右面图片 -->
        <div class="out_right">
            <img src="https://timgsa.baidu.com/timg?image&amp;quality=80&amp;size=b9999_10000&amp;sec=1553678403565&amp;di=8270b43535f2d4dbd97e03adffe0bb7f&amp;imgtype=0&amp;src=http%3A%2F%2Fb-ssl.duitang.com%2Fuploads%2Fitem%2F201406%2F12%2F20140612193057_JYL2m.thumb.700_0.jpeg" class="pic">
        </div>
        <!--上面图片 -->
        <div class="out_top">
            <img src="https://timgsa.baidu.com/timg?image&amp;quality=80&amp;size=b9999_10000&amp;sec=1553678403564&amp;di=7c6f066b3151993f1319707ff9622775&amp;imgtype=0&amp;src=http%3A%2F%2Fb-ssl.duitang.com%2Fuploads%2Fitem%2F201406%2F15%2F20140615122443_jiYKQ.jpeg" class="pic">
        </div>
        <!--下面图片 -->
        <div class="out_bottom">
            <img src="https://timgsa.baidu.com/timg?image&amp;quality=80&amp;size=b9999_10000&amp;sec=1553678403563&amp;di=ebfbd4c855b6a6ebf803a3f9fad9754f&amp;imgtype=0&amp;src=http%3A%2F%2Fi0.hdslb.com%2Fbfs%2Farticle%2F8b344b9bf5c7219460ceb70dcbb19484f2862a2f.png" class="pic">
        </div>

        <!--小正方体 -->
        <span class="in_front">
                <img src="https://timgsa.baidu.com/timg?image&amp;quality=80&amp;size=b9999_10000&amp;sec=1553678403563&amp;di=2aa513aa9e7a7c038639c1e70d08fc32&amp;imgtype=0&amp;src=http%3A%2F%2Fimgq.duitang.com%2Fuploads%2Fitem%2F201406%2F12%2F20140612201307_nhCHG.jpeg" class="in_pic">
            </span>
        <span class="in_back">
                 <img src="https://timgsa.baidu.com/timg?image&amp;quality=80&amp;size=b9999_10000&amp;sec=1553678403562&amp;di=e0ec2c8307b757a1c89af7876825ce18&amp;imgtype=0&amp;src=http%3A%2F%2Fimg5.duitang.com%2Fuploads%2Fitem%2F201406%2F14%2F20140614142843_tYFP3.thumb.700_0.jpeg" class="in_pic">
            </span>
        <span class="in_left">
                <img src="https://timgsa.baidu.com/timg?image&amp;quality=80&amp;size=b9999_10000&amp;sec=1553678403560&amp;di=8592a34c2e3d94680840d9f9b532f27c&amp;imgtype=0&amp;src=http%3A%2F%2Fb-ssl.duitang.com%2Fuploads%2Fitem%2F201406%2F14%2F20140614142944_wcRkS.png" class="in_pic">
            </span>
        <span class="in_right">
                <img src="https://timgsa.baidu.com/timg?image&amp;quality=80&amp;size=b9999_10000&amp;sec=1553678403555&amp;di=261086b6625f1b954ec176cf0684880a&amp;imgtype=0&amp;src=http%3A%2F%2Fi0.hdslb.com%2Fbfs%2Farticle%2F920df50533d2408c87066ef560a851f4846f19e5.jpg" class="in_pic">
            </span>
        <span class="in_top">
                <img src="https://timgsa.baidu.com/timg?image&amp;quality=80&amp;size=b9999_10000&amp;sec=1553678403553&amp;di=47beea55736f531a56b117d091d14253&amp;imgtype=0&amp;src=http%3A%2F%2Fi0.hdslb.com%2Fbfs%2Farticle%2Ff5f4164deeda7b3624644bdf98ca5e7216770c27.jpg" class="in_pic">
            </span>
        <span class="in_bottom">
                <img src="https://timgsa.baidu.com/timg?image&amp;quality=80&amp;size=b9999_10000&amp;sec=1553678403552&amp;di=a260e79961f1f8c3b25068fcba055686&amp;imgtype=0&amp;src=http%3A%2F%2Fi0.hdslb.com%2Fbfs%2Farticle%2Fb7476da2e60a23865c3bc70ffd619ed81767081b.jpg" class="in_pic">
            </span>

    </div>
    <style>
        /*最外层容器样式*/
        .wrap {
            width: 100px;
            height: 100px;
            margin: 150px;
            position: relative;
        }

        /*得到立方体效果*/
        .cube {
            width: 50px;
            height: 50px;
            margin: 0 auto;
			margin-left: 300px;
            transform-style: preserve-3d;
            /*设置动画播放样式:动画对象 播放速度 时间 播放次数*/
            animation: rotate linear 20s infinite;
        }

        /*动画旋转的方式*/
        /*得到动画效果*/
        @-moz-keyframes rotate {                     /*firefox*/
            from {
                transform: rotateX(0deg) rotateY(0deg);
            }
            to {
                transform: rotateX(360deg) rotateY(360deg);
            }
        }
        @-webkit-keyframes rotate {                /*sofari chrome*/
            from {
                transform: rotateX(0deg) rotateY(0deg);
            }
            to {
                transform: rotateX(360deg) rotateY(360deg);
            }
        }
        @-o-keyframes rotate {                    /*opera*/
            from {
                transform: rotateX(0deg) rotateY(0deg);
            }
            to {
                transform: rotateX(360deg) rotateY(360deg);
            }
        }
        /*每张图片的样式*/
        .cube div {
            position: absolute;
            width: 200px;
            height: 200px;
            opacity: 0.8;
            /*过渡效果*/
            transition: all .4s;
        }

        /*定义所有图片样式*/
        .pic {
            width: 200px;
            height: 200px;
        }

        .cube .out_front {
            transform: rotateY(0deg) translateZ(100px);
        }

        .cube .out_back {
            transform: translateZ(-100px) rotateY(180deg);
        }

        .cube .out_left {
            transform: rotateY(-90deg) translateZ(100px);
        }

        .cube .out_right {
            transform: rotateY(90deg) translateZ(100px);
        }

        .cube .out_top {
            transform: rotateX(90deg) translateZ(100px);
        }

        .cube .out_bottom {
            transform: rotateX(-90deg) translateZ(100px);
        }

        /*定义小正方体样式*/
        .cube span {
            display: block;
            width: 100px;
            height: 100px;
            position: absolute;
            top: 50px;
            left: 50px;
        }

        .cube .in_pic {
            width: 100px;
            height: 100px;
        }

        .cube .in_front {
            transform: rotateY(0deg) translateZ(50px);
        }

        .cube .in_back {
            transform: translateZ(-50px) rotateY(180deg);
        }

        .cube .in_left {
            transform: rotateY(-90deg) translateZ(50px);
        }

        .cube .in_right {
            transform: rotateY(90deg) translateZ(50px);
        }

        .cube .in_top {
            transform: rotateX(90deg) translateZ(50px);
        }

        .cube .in_bottom {
            transform: rotateX(-90deg) translateZ(50px);
        }

        /*鼠标移入后样式*/
        .cube:hover .out_front {
            transform: rotateY(0deg) translateZ(200px);
        }

        .cube:hover .out_back {
            transform: translateZ(-200px) rotateY(180deg);
        }

        .cube:hover .out_left {
            transform: rotateY(-90deg) translateZ(200px);
        }

        .cube:hover .out_right {
            transform: rotateY(90deg) translateZ(200px);
        }

        .cube:hover .out_top {
            transform: rotateX(90deg) translateZ(200px);
        }

        .cube:hover .out_bottom {
            transform: rotateX(-90deg) translateZ(200px);
        }
    </style>
</div>
</body>
</html>
