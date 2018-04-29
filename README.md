# Hugo, Minify and S3Deploy

Container with the three tools you need for a static site in AWS.

## Usage in a CD pipeline

```
git clone <your website>
```

Then invoke hugo:
```
hugo -v
```

Minify:
```
minify
```

And upload your files to your S3 bucket:
```
s3deploy
```
