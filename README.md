# Hello-yjj
pushState()有三个参数:state对象，标题(现在是被忽略，未作处理)，URL(可选)。具体细节：

·        state对象 –state对象是一个JavaScript对象，它关系到由pushState()方法创建出来的新的history实体。用以存储关于你所要插入到历史 记录的条目的相关信息。State对象可以是任何Json字符串。因为firefox会使用用户的硬盘来存取state对象，这个对象的最大存储空间为640k。如果大于这个数 值，则pushState()方法会抛出一个异常。如果确实需要更多的空间来存储，请使用本地存储。

·        title—firefox现在回忽略这个参数，虽然它可能将来会被使用上。而现在最安全的使用方式是传一个空字符串，以防止将来的修改。或者可以传一个简短的标题来表示state

·        URL—这个参数用来传递新的history实体的URL，注意浏览器将不会在调用pushState()方法后加载这个URL。但也许会过一会尝试加载这个URL。比如在用户重启了浏览器后，新的url可以不是绝对路径。如果是相对路径，那么它会相对于现有的url。新的url必须和现有的url同域，否则pushState()将抛出异常。这个参数是选填的，如果为空，则会被置为document当前的url。


# blok  
无
# name
yjj
#性别
女
