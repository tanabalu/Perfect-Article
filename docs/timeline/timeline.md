# 每日学习

<div class="timeline-container">
    <div class="timeline-body">
        <div class="timeline-main">
            <div class="timeline-time">2019/08/24</div>
            <div class="timeline-content">完成了jenkins自动部署war包到tomcat的功能。</div>
        </div>
    </div>
    <div class="timeline-body">
        <div class="timeline-main">
            <div class="timeline-time">2019/08/23</div>
            <div class="timeline-content">1、解决了calculator项目Java代码不能发布到github的问题。</div>
            <div class="timeline-content">解决办法是新建了一个文件夹，将代码文件拷贝到新文件夹中，然后在新文件夹跟远程建立连接，把本地代码强制推送到远程，覆盖掉远程的代码。虽然解决了问题，但是我还是没发现在之前的文件夹中java代码没有上传是个什么原因。</div>
            <div class="timeline-content">2、修改了jenkins的配置，Maven项目在jenkins上构建成功。</div>
        </div>
    </div>
    <div class="timeline-body">
        <div class="timeline-main">
            <div class="timeline-time">2019/08/21</div>
            <div class="timeline-content">从昨晚到今天凌晨两点：尝试在Jenkins上配置Maven项目，未成功。</div>
        </div>
    </div>
    <div class="timeline-body">
        <div class="timeline-main">
            <div class="timeline-time">2019/08/20</div>
            <div class="timeline-content">codepen：<a href="https://codepen.io/awhitemouse/pen/ZEzpPgN" target="_blank">CSS评分</a>。</div>
        </div>
    </div>
    <div class="timeline-body">
        <div class="timeline-main">
            <div class="timeline-time">2019/08/18</div>
            <div class="timeline-content">准备将<a href="https://github.com/WebStackPage/WebStackPage.github.io" target="_blank">网址导航项目</a>由静态网页项目改装为React项目，减少重复代码。</div>
        </div>
    </div>
    <div class="timeline-body">
        <div class="timeline-main">
            <div class="timeline-time">2019/08/16</div>
            <div class="timeline-content">配置Jenkins发布项目到指定目录。另外，Jenkins已经实现自动发布。</div>
        </div>
    </div>
    <div class="timeline-body">
        <div class="timeline-main">
            <div class="timeline-time">2019/08/15</div>
            <div class="timeline-content">更新Perfect-Article</div>
        </div>
    </div>
    <div class="timeline-body">
        <div class="timeline-main">
            <div class="timeline-time">2019/08/14</div>
            <div class="timeline-content">在markdown中编辑html</div>
        </div>
    </div>
</div>

<style>
    .timeline-container {
        width: 100%;
        padding-left: 10px;
        position: relative;
        color: #fff;
    }

    .timeline-body {
        position: relative;
        border-left: 2px solid #ddd;
        padding: 20px;
    }

    .timeline-body::before {
        content: '';
        position: absolute;
        top: 30px;
        left: -7px;
        width: 12px;
        height: 12px;
        border-radius: 50%;
        background-color: #0081ff;
    }

    .timeline-body::after {
        content: '';
        position: absolute;
        top: 33px;
        left: -4px;
        width: 6px;
        height: 6px;
        border-radius: 50%;
        background-color: #fff;
    }

    .timeline-main {
        padding: 10px 15px 15px 15px;
        background-image: linear-gradient(45deg, #0081ff, #1cbbb4);
    }

    .timeline-time {
        padding: 2px;
        min-width: 0;
        border-radius: 5px;
        font-weight: 700;
        font-size: 18px;
    }

    .timeline-content {
        margin-top: 5px;
    }
</style>
