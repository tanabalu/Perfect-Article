# 每日学习

<div class="timeline-container">
    <div class="timeline-body">
        <div class="timeline-main">
            <div class="timeline-time">2019/09/25</div>
            <div class="timeline-content">1、学习apply和call：<a href="https://juejin.im/post/5d8b3521e51d457825210a1a" target="_blank">帮你快速理解apply和call</a>；
            </div>
            <div class="timeline-content">2、学习<a href="http://es6.ruanyifeng.com/#docs/module" target="_blank">前端模块化</a>；</div>
            <div class="timeline-content">3、手写eventProxy.js。</div>
        </div>
    </div>
    <div class="timeline-body">
        <div class="timeline-main">
            <div class="timeline-time">2019/09/24</div>
            <div class="timeline-content">1、跟着教程学习用react16、next.js搭建博客，预计可能还会用到koa；</div>
            <div class="timeline-content">2、安装Gridea，准备以后遇到困难，将解决问题的过程发布在这里。内容还需要再手动同步一下。</div>
        </div>
    </div>
    <div class="timeline-body">
        <div class="timeline-main">
            <div class="timeline-time">2019/09/23</div>
            <div class="timeline-content">问：如何解决首页白屏问题？</div>
            <div class="timeline-content">答：</div>
            <div class="timeline-content">1、webpack打包减少js体积；按需加载；</div>
            <div class="timeline-content">2：服务端渲染，服务端的效率高于浏览器；</div>
            <div class="timeline-content">3：页面loading和骨架屏。</div>
        </div>
    </div>
    <div class="timeline-body">
        <div class="timeline-main">
            <div class="timeline-time">2019/09/22</div>
            <div class="timeline-content">问：react里的Link标签和a标签有什么区别？</div>
            <div class="timeline-content">答：</div>
            <div class="timeline-content">1、Link标签如果绑定了onClick事件，就会默认组件跳转事件；</div>
            <div class="timeline-content">2：Link的跳转是使用hash跳转，不是页面跳转，只会更新对应的Router，不会刷新整个页面。</div>
        </div>
    </div>
    <div class="timeline-body">
        <div class="timeline-main">
            <div class="timeline-time">2019/09/14</div>
            <div class="timeline-content">1、把弹窗组件加到wxcool中，待demo测试。</div>
            <div class="timeline-content">2、配置github图床。</div>
        </div>
    </div>
    <div class="timeline-body">
        <div class="timeline-main">
            <div class="timeline-time">2019/08/29</div>
            <div class="timeline-content">codepen：<a href="https://codepen.io/awhitemouse/pen/zYOzZKa" target="_blank">CSS单选框</a></div>
        </div>
    </div>
    <div class="timeline-body">
        <div class="timeline-main">
            <div class="timeline-time">2019/08/28</div>
            <div class="timeline-content">1、拆分root和calculator，拆分完后发现有问题。</div>
            <div class="timeline-content">拆分后发现root没有war包，也就不能被自动部署到tomcat中。同时，calculator也因为路径问题而无法访问。</div>
            <br/>
            <div class="timeline-content">前些天一直在做书院首页的需求，一直到昨天晚上上线，我才算心安了。</div>
        </div>
    </div>
    <div class="timeline-body">
        <div class="timeline-main">
            <div class="timeline-time">2019/08/25</div>
            <div class="timeline-content">1、尝试配置钩子程序自动触发jenkins构建，未成功，于是将配置复原。</div>
            <div class="timeline-content">2、更新WxCool：添加节流防抖函数；优化Hapi的封装；添加携带promise的请求封装。</div>
        </div>
    </div>
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
    
    .timeline-content a {
        color: greenyellow !important;
    }
</style>
