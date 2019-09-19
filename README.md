# aws-s3


[使用全域組態物件](https://docs.aws.amazon.com/zh_tw/sdk-for-javascript/v2/developer-guide/global-config-object.html)
credentials 必要。 指定判斷服務和資源存取所用的登入資料。  
region 必要。 指定為服務提出請求的區域。  


region [区域和可用区](https://docs.aws.amazon.com/zh_cn/AWSEC2/latest/UserGuide/using-regions-availability-zones.html)  


| ap-northeast-1  | 亚太区域（东京）  |   
| ap-northeast-2  | 亚太区域（首尔）  |   


# Uploading Photos to Amazon S3  

[從瀏覽器上傳相片至 Amazon S3](https://docs.aws.amazon.com/zh_tw/sdk-for-javascript/v2/developer-guide/s3-example-photo-album.html)  
[上傳相片至 Amazon S3：完整程式碼](https://docs.aws.amazon.com/zh_tw/sdk-for-javascript/v2/developer-guide/s3-example-photo-album-full.html)  

[aws s3直接通过JavaScript上传文件](https://blog.csdn.net/qq1147093833/article/details/80267542)  
[将照片通过浏览器上传到Amazon S3服务](https://blog.csdn.net/sdiudui/article/details/79928631)  

[vue-s3-dropzone](https://madewithvuejs.com/vue-s3-dropzone) - Made with Vue.js    
[Amazon S3 Browser Upload](https://www.shanestillwell.com/2018/09/02/amazon-file-upload/)  


## vue-s3-dropzone

[vue-s3-dropzone](https://madewithvuejs.com/vue-s3-dropzone)    
[DropzoneJS](https://www.dropzonejs.com/) is an open source library that provides drag’n’drop file uploads with image previews.  
[Dropzone.js](https://gitlab.com/meno/dropzone) is a light weight JavaScript library that turns an HTML element into a dropzone.
`npm i dropzone --save`  
[dropzonejs doc ](ttps://www.dropzonejs.com/) 

# vue 

`vue create frontend`  Vue CLI v3.6.2  

? Please pick a preset: Manually select features
? Check the features needed for your project: Babel, Router, Vuex, Linter
? Use history mode for router? (Requires proper server setup for index fallback in production) Yes
? Pick a linter / formatter config: Basic
? Pick additional lint features: (Press <space> to select, <a> to toggle all, <i> to invert selection)Lint on save
? Where do you prefer placing config for Babel, PostCSS, ESLint, etc.? In dedicated config files
? Save this as a preset for future projects? No

```
$ cd frontend
$ yarn serve
```