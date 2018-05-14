# ThirdPartyLogin-JS-SDK
使用JavaScript SDK实现网站通过google、facebook、TwitterlinkedIn、VK等社交媒体实现免注册快捷登录。

各个登陆需要把都 谷歌client_id 或者 facebook的appId、linkedin的api_key 配置上按钮才会生效。

注意：google帐户的邮箱可能会更改，因此请勿使用它来标识用户，请使用帐户的ID。

facebook登陆要注意，有效 OAuth 跳转 URI要是https的，必须https

linkedin要注意，onLinkedInLoad 方法里面要写  IN.User.isAuthorized(); 判断下是否授权过授。

vkontakte要注意，好像获取不到邮箱，好像是限制获取到邮箱，还有俄罗斯的姓和名是反的，我只获取到了first_name。

twitter开发者注册应用要国外的手机号，然并木有。

QQ：1014558384