aws s3 website s3://www.billhive.org --index-document index.html --error-document index.html

aws s3api put-bucket-policy --bucket www.billhive.org --policy file://bucket-policy.json

aws s3 sync out/ s3://www.billhive.org