# html

`hexo init blog`  
`cd blog`    
`hexo s`  

`hexo g` public  
`hexo d` deploy  

## [hexo-theme-doc](https://github.com/zalando-incubator/hexo-theme-doc)  

_config.yaml

```js
# URL
## If your site is put in a subdirectory, set url as 'http://yoursite.com/child' and root as '/child/'
root: /html

# Deployment
## Docs: https://hexo.io/docs/deployment.html
deploy:
    type: git
    repository: https://github.com/JacobHsu/html
    branch: gh-pages
```