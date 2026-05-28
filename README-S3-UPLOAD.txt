Upload the CONTENTS of this folder to your S3 bucket, not the folder itself.

Required files at the bucket root:
- index.html
- styles.css
- script.js
- images/

For S3 static website hosting, set:
- Index document: index.html
- Error document: index.html

If using CloudFront, invalidate /* after upload.
