小程序技术架构：
    
    原生小程序 + typescript +less + vant

安装工具：
    
    yarn

新增依赖：

    cd miniprogram

    yarn add xxx

分包：
    
    暂无分包

七牛云项目地址仓库：
    
    static/BKRYB/mini（小程序端） static/BKRYB/pc（pc端） 

**ts参数类型校验尽可能定义确定类型，勿大范围使用any** 

分支结构：

    master 线上分支
    test 测试分支
    ...
    
    开发自创分支，向test/master merge即可；保证多人协作尽可能避免冲突

目录结构：

    apis：所有接口接口走一层封装，方便不同页面调用产生多处重复代码

    assets：静态资源文件

    components：全局自定义组件

    config：全局配置文件 interface.ts为所有接口地址文件，config.ts为全局通用配置参数

    types：全局通用或者常用 ts 类型集合

    utils：工具库



![Image text](https://resource.boka.vc/BKRYB/mini/WechatIMG247.png)


