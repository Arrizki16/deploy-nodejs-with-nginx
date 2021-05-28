# deploy-nodejs-with-nginx

If you dont have node js project you have to create. and move to your project folder then setting your npm

1. Install current nodejs
```
curl -sL https://deb.nodesource.com/setup_15.x | sudo -E bash -
apt-get install -y nodejs
```
2. Check node js and nmp version
```
node -v
npm -v
```
3. Install npm
```
npm install
```
then you need to install newest version npn
```
npm install -g npm@next
```
4. build npm
```
npm run build
```
5. start
```
npm start
```


## Some Error
1. sh: 1: craco: Permission denied  
its happen because u forget to install npm before running npm build
```
npm install
```
2. Failed to load config "react-app" to extend from.
```

```
3. File project permission
```
chown -R www-data:www-data project-folder-path
```
4. Failed to compile  
![Screenshot_2021-05-28_09-14-48](https://user-images.githubusercontent.com/55046884/119919675-22cfad00-bf95-11eb-93f9-6386154a5fa4.png)
```

```
