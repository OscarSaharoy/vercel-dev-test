# vercel-dev-test

bug repro:

```
git clone git@github.com:OscarSaharoy/vercel-dev-test.git
cd vercel-dev-test
vercel dev
```
Then go to [http://localhost:3000](http://localhost:3000) in firefox and see the error in the console, check the Content-Type of the response for the request to http://localhost:3000/css/test.css

![image](https://user-images.githubusercontent.com/29902113/220139787-08da7050-cff4-4637-81ee-9560828c74bb.png)
![image](https://user-images.githubusercontent.com/29902113/220140032-3676f303-2ae5-4afa-944e-10fe1500346d.png)

Its the filename for some reason
