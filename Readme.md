readme file

create iam user and provided permission to elastic beanstalk admin access

create access key and secret key for that user using cli mode when asked in gui

goto github repo and select the repo called docker-course-compose-into-emoji-app and right side top you'll see the settings, secrets and variables -- actions--repository secrets add access key and secret key which we created for that user

in elastic bean stack application name emoji-tester it will auto pick env name -- runtime select Docker -- role create elastic beanstalk service role and s3 role to ec2instance profile -- vpc default --availability select any two zone -- security group default subnet default health check basic public ip address enabled managed updates uncheck env property ENV_FLASK - Development

just update
