# React Router Load On Demand

## How to run the example

Checkout this repo by `git clone` or download the ziped file.

```
git clone https://github.com/chyingp/react-router-load-on-demand.git
```

Install `react-tools` to compile `jsx` to `js` 

```
npm install -g react-tools
```

Enter the `example` folder via command line

```
cd example
```

Then run `jsx` to compile jsx format file to normal js file.

```
jsx -w jsx js
```

Next start a mini server. (Thanks to https://gist.github.com/ryanflorence/701407)

```
node server.js
```

Finally, visits it in browser http://localhost:8888/

## See the result

You can see the beautiful page.

![image](https://cloud.githubusercontent.com/assets/2383346/9149609/558d1784-3de4-11e5-9129-f358a5c2f755.png)


Only `home.js` was loaded at first view.

![image](https://cloud.githubusercontent.com/assets/2383346/9149601/27c9ce00-3de4-11e5-8b99-149d9544df79.png)

Click the `about` link

![image](https://cloud.githubusercontent.com/assets/2383346/9149612/6fd1126c-3de4-11e5-9c51-e939c6036334.png)

The `about` component was shown.

![image](https://cloud.githubusercontent.com/assets/2383346/9149613/7d14c8ec-3de4-11e5-81a0-cd46f9cc8bd4.png)

Only at this time, the `about` component was loaded on demand.

![image](https://cloud.githubusercontent.com/assets/2383346/9149620/a7f95dca-3de4-11e5-8576-ba7e5104ddad.png)


