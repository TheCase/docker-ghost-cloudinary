## ghost-cloudinary

a simple wrapper for the Ghost blog platform that adds the Cloudinary storage adapter for image storage.

Add your CLOUDINARY_URL as an environment varible.

```
docker run -d -p 8080:2368 -E CLOUDINARY_URL="<key>:<secret>@<site>" thecase/ghost-cloudinary
```
