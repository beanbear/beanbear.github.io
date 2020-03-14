---
title: Moment
---
<link rel="stylesheet" href="./moment.css">

<div id="primary" class="content-area" style="">
    <main id="main" class="site-main" role="main">
        <div id="moment_content">
            <ul class="cbp_tmtimeline">
                <li> <span class="moment_author_img"><img src="/img/favicon.png" class="avatar avatar-48 zhuan" width="48" height="48"></span>
                    <a class="cbp_tmlabel" href="">
                        <p></p>
                        <p>背景音乐一首~</p>
                        <iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width=298 height=52 src="//music.163.com/outchain/player?type=2&id=1338809890&auto=1&height=32"></iframe>
                        <p></p>
                        <p class="moment_time"><i class="fa fa-clock-o"></i>
                            2020年3月14日00:15:05
                        </p>
                    </a>
                </li>
                 <li> <span class="moment_author_img"><img src="/img/favicon.png"" class="avatar avatar-48 zhuan" width="48" height="48"></span>
                    <a class="cbp_tmlabel" href="">
                        <p></p>
                        <img src="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1582636990314&di=2421dcd34e1cc519b7f7f9559afbe7b1&imgtype=0&src=http%3A%2F%2Fpics1.baidu.com%2Ffeed%2Fb17eca8065380cd7531865282a19873258828151.jpeg%3Ftoken%3Dce6f76a2b9dc38c02c91acfc2a4bb8d8%26s%3D3C79EF14C510746516F547E003007036" height="200" width="100" />
                        <p>武汉加油！中国加油！</p>
                        <p></p>
                        <p class="moment_time"><i class="fa fa-clock-o"></i>
                            2020年3月13日23:58:44
                        </p>
                    </a>
                </li>
                <li> <span class="moment_author_img"><img src="/img/favicon.png" class="avatar avatar-48 zhuan" width="48" height="48"></span>
                    <a class="cbp_tmlabel" href="">
                        <p></p>
                        <p>第一个说说</p>
                        <p></p>
                        <p class="moment_time"><i class="fa fa-clock-o"></i>
                            2020年3月13日22:58:33
                        </p>
                    </a>
                </li>
            </ul>
        </div>
</div>
<script type="text/javascript">
    (function () {
        var oldClass = "";
        var Obj = "";
        $(".cbp_tmtimeline li").hover(function () {
            Obj = $(this).children(".moment_author_img");
            Obj = Obj.children("img");
            oldClass = Obj.attr("class");
            var newClass = oldClass + " zhuan";
            Obj.attr("class", newClass);
        }, function () {
            Obj.attr("class", oldClass);
        })
    })
</script>