## aws-guardduty-cf-with-lambda

#### Description:  
<p> This Cloudformation template enables Guardduty and allows publishing destination.
Cloudformation for guardduty doesn't have resource that allows publishing to a destination natively.
In this template, an inline lambda is used to accomplish that task, by creating an S3 bucket and publishing guardduty findings to it.</p>
