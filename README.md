# s3-sync-plugin

- name: Sync to S3
  uses: <your GitHub username>/<your repository name>@main
  with:
    source: <your source directory or file path>
    destination: <your S3 bucket path>
    aws_access_key_id: ${{ secrets.AWS_ACCESS_KEY_ID }}
    aws_secret_access_key: ${{ secrets.AWS_SECRET_ACCESS_KEY }}


