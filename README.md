# s3extractor 🔍
Bash Script to extract s3 buckets from JS files of the target and check their permissions.

- ⚙ How it works: 
1. Finds Subdomains of the target
2. Extracts JavaScript files from the target and its subdomains
3. Finds S3 buckets in those JS files
4. Checks Permissions of the buckets (CRUD operations) using aws cli

# 📝
- S3 buckets can also be found in Android Applications. [APKnuke](https://github.com/utkarsh24122/apknuke) and [APKanalzser](https://github.com/utkarsh24122/ApkAnalyzer) can be used to extract S3 buckets from an APK
- A misconfigured S3 bucket may lead to a Subdomain takeover

# Setup 🔧
1. Make sure you have aws cli configured. [Learn How](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-configure.html)
2. Check if you have the [required tools](https://github.com/AnonymousJass/s3extractor/blob/main/Required_tools.md) installed
3. Run:
```
git clone https://github.com/AnonymousJass/s3extractor.git ; cd s3extractor
chmod +x s3extract.sh
```

# Usage 🎮
``` 
./s3extract.sh target.com 
```


