# terraform-s3-backend-lab week 13

## When is the state file created?
The state file is created after you run ```terraform apply```

## When is the lock file present?
The lock file is present whenever you run ```terraform apply``` but haven't confirmed the changes (Didn't write yes when prompted).    

## Is the lock file always in the bucket after it is created?
The lock file is deleted after you run ```terraform apply``` and confirmed the changes.

## Only state file in S3
<img width="975" height="524" alt="image" src="https://github.com/user-attachments/assets/e93b3b13-856e-48ad-b566-3e07fc1ea34a" />

## State and lock files in S3
<img width="975" height="526" alt="image" src="https://github.com/user-attachments/assets/b67ff0c6-6d19-41fd-b95a-c5b5af1e3cad" />
