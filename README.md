# Example

```
docker run \
-e AWS_ACCESS_KEY_ID=$AWS_ACCESS_KEY_ID \
-e AWS_SECRET_ACCESS_KEY=$AWS_SECRET_ACCESS_KEY \
-e IMGOP_BUCKET=$IMGOP_BUCKET \
--restart=always \
-p 4000:3000 \
imgop
```
