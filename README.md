## 欢迎来到2horse的技术博客

  本博客目的有两个，一是记录工作和学习的一些问题，方便查看和总结. 二是希望能帮助到有需要的朋友

### ruby
  不同于 development，如果在 production 环境出现例外错误，不会显示程式 call stack 讯息，而是回传 public/500.html 页面。
  
# Full error reports are disabled and caching is turned on
 config.consider_all_requests_local       = false
 config.action_controller.perform_caching = true


