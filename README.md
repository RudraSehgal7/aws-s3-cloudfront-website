# aws-s3-cloudfront-website
“AWS Cloud projects for S3, CloudFront, Lambda, IAM, CloudWatch — fully documented for learning &amp; resume”



## Steps to Implement (AWS)
1. **Create S3 Bucket**
   - Enable "Static Website Hosting".
   - Upload `index.html` and `error.html`.

2. **Set Bucket Policy**
   - Allow public read (or OAI for private access via CloudFront).

3. **Create CloudFront Distribution**
   - Set S3 bucket as origin.
   - Enable HTTPS using ACM certificate.
   - Configure default root object (`index.html`).

4. **IAM Access Control (Optional)**
   - Use IAM roles or policies for deployment.
   - Example policy included in `iam-policy.json`.

5. **Test Website**
   - Access via CloudFront domain to ensure HTTPS works.

## Files in this Repo
- `index.html` → Sample homepage.
- `er.html` → Sample error page.
- `iam-policy.json` → Example IAM policy for S3 read-only access.
- `architecture.txt` → Text-based diagram for reference.

## Key Concepts Covered
- AWS S3 (Static Website Hosting)
- CloudFront CDN + HTTPS
- IAM Policies & Least Privilege
- Eventual Cloud Security Concepts

---

## Author
Rudrasehgal | Cybersecurity & Cloud Enthusiast
