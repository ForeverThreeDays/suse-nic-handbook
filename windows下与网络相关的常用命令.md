# windows下与网络相关的常用命令
## 一、cmd终端相关  
### cmd终端启动  
如何启动cmd终端？首先，你得有一台Windows系统的电脑，其次保证电脑能够正常启动，如果能做到的话，那么请打开你喜欢的<del><b>游戏</b></del>Windows搜索框，输入cmd这三个字符。
<center><img src="https://threedays-1256422565.cos.ap-chengdu.myqcloud.com/img/QQ%E5%9B%BE%E7%89%8720200917203634.png"></center>  


一般直接打开，需要权限的情况下，请点击以管理员身份运行。  

当然，作为网管中心的维护人员，有时我们需要一点点<del><b>装逼</b></del>实用技能。
同时按下<kbd>Win</kbd>+<kbd>R</kbd>,如果按对了应该是这样的： 


<center><img src="https://threedays-1256422565.cos.ap-chengdu.myqcloud.com/img/QQ%E6%88%AA%E5%9B%BE20200917210133.png"></center>
然后输入cmd，按下<kbd>enter</kbd>键，就可以看到激动人心的cmd界面了:  


<center><img src="https://threedays-1256422565.cos.ap-chengdu.myqcloud.com/img/QQ%E6%88%AA%E5%9B%BE20200917210712.png"></center>
<center><img src="https://threedays-1256422565.cos.ap-chengdu.myqcloud.com/img/QQ%E6%88%AA%E5%9B%BE20200917210610.png"></center>
找找上面两张图有什么不同。<del>不准吐槽用户名！！！</del>    


希望你已经看出来了，最关键的不同之处在于图片左上角显示的一个是管理员而另一个是cmd的路径。  


在前面我并没有介绍如何在运行界面以管理员权限运行cmd<del>因为不会</del>。其实也并不复杂，前几步操作相同，只有最后一步，将<kbd>enter</kbd>换成<kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>enter</kbd>。这样你又能看到这黑乎乎的cmd界面了。

## 二、常用网络相关命令
经过了上面的稍微有点啰嗦的介绍以后，你应该学会如何打开cmd终端了，然后你可以用这个终端干一些<del>不可名状</del>有趣的事了。
### ipconfig命令
ipconfig命令是常用的命令之一，在cmd终端运行该命令后，你会看见像下图一样的东西：


<center><img src="https://threedays-1256422565.cos.ap-chengdu.myqcloud.com/img/QQ%E5%9B%BE%E7%89%8720200918163134.png"/></center>


图中有个叫做IPv4地址的东西，你现在只需要一直盯着它，等到你觉得它害羞了为止。其他的内容我会在后面提到，所以现在你只需要继续看下去，知道有这个东西就行。  
### ipconfig /release和ipconfig /renew命令
注意到了吗？在ipconfig后面多了两个新的东西，分别是release和renew。如果你的英文水平还行的话大概还是能看出这两个单词的意思，<del>恰巧我英语是真的不行</del>，所以就不解释单词的意思了。
解释一下命令的用途<del>我还是行的</del>，<b>ipconfig /release</b>命令的作用是释放IPv4地址，<b>ipconfig /renew</b>的作用是更新IPv4地址。

什么？你还是想知道什么是IPv4地址？<del>不会吧，不会吧,真的有人问我那么尴尬的问题？</del>那我就稍稍打个比方吧：小王想给同在自流井大学某个T同学寄个包裹，<del>不愧是小王，真的是条懒狗</del>于是我们的小王同志找上了正好闲的无聊的M同学，给了M同学好不容易打听到的T同学的地址，让M同学将包裹送到T同学的手上。但是，小王同学发现，他打听到的地址错了，于是小王同志给M发了条内容为有内鬼，终止交易的短信，在M同学发来的满屏问号当中，小王同学将重新打听到的地址发给了M同学，最后包裹送到了T同学的手上，我们的M同学也收到了此次跑腿的报酬，结局真是可喜可贺。


我们采用类比的手法，将IPv4地址当作是小王打听到的地址，小王分别执行了收回地址和重新取得地址的动作，这两个动作便和之前提到的两个命令有一定的相似之处。