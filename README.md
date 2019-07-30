# html
 

## [hexo-theme-doc](https://github.com/zalando-incubator/hexo-theme-doc)  

[Quick Start](https://zalando-incubator.github.io/hexo-theme-doc/get-started.html)  

`$ git clone https://github.com/zalando-incubator/hexo-theme-doc-seed.git`  

rename `hexo-theme-doc-seed` to `doc`  

`npm install`  

`hexo s` serve   
`hexo g` public  
`hexo d` deploy  

`npm install hexo-deployer-git --save`  


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