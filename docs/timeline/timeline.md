# 每日学习

<div class="timeline-container">
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
