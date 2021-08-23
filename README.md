# Social Scripts 🚀

### Your one-stop-shop to automate your social media! 🔥

### Copy and Paste the appropriate script into your console, and BOOM!

<!-- toc -->

- [Twitter](#twitter)
  * [Like/Favourite All Tweets On Page](#likefavourite-all-tweets-on-page)
  * [Unlike/Unfavourite All Tweets On Page](#unlikeunfavourite-all-tweets-on-page)
  * [Follow All Users On Page](#follow-all-users-on-page)
  * [Unfollow All Users On Page](#unfollow-all-users-on-page)
- [GitHub](#github)
  * [Follow All Users On Page](#follow-all-users-on-page-1)
  * [Unfollow All Users On Page](#unfollow-all-users-on-page-1)
  * [Star All Repositories On Page](#star-all-repositories-on-page)
  * [Unstar All Repositories On Page](#unstar-all-repositories-on-page)

<!-- tocstop -->

# Twitter

## Like/Favourite All Tweets On Page
```javascript
var inputs = document.querySelectorAll('div[data-testid="like"]'); 
for(var i=0; i<inputs.length;i++) { inputs[i].click(); }
```

## Unlike/Unfavourite All Tweets On Page
```javascript
var inputs = document.querySelectorAll('div[data-testid="unlike"]'); 
for(var i=0; i<inputs.length;i++) { inputs[i].click(); }
```

## Follow All Users On Page
```javascript
var inputs = document.querySelectorAll('div[data-testid*="follow"]'); 
for(var i=0; i<inputs.length;i++) { inputs[i].click(); }
```

## Unfollow All Users On Page
```javascript
var inputs = document.querySelectorAll('div[data-testid*="unfollow"]'); 
for(var i=0; i<inputs.length;i++) { inputs[i].click(); }
```

# GitHub

## Follow All Users On Page
```javascript
var inputs = document.querySelectorAll('input[value="Follow"]'); 
for(var i=0; i<inputs.length;i++) { inputs[i].click(); }
```

## Unfollow All Users On Page
```javascript
var inputs = document.querySelectorAll('input[value="Unfollow"]'); 
for(var i=0; i<inputs.length;i++) { inputs[i].click(); }
```

## Star All Repositories On Page
```javascript
var inputs = document.querySelectorAll('button[value="Star"]'); 
for(var i=0; i<inputs.length;i++) { inputs[i].click(); }
```

## Unstar All Repositories On Page
```javascript
var inputs = document.querySelectorAll('button[value="Unstar"]'); 
for(var i=0; i<inputs.length;i++) { inputs[i].click(); }
```
