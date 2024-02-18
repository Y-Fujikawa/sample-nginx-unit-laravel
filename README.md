# sample-roadrunner-laravel
引用元：https://github.com/il-m-yamagishi/laravel-loadtest  
上記から、RoadRunnerのみにしたリポジトリ

## 疎通確認

```shell
curl -X POST -d "name=example&email=example@laravel-load.test&password=secretsecret" localhost:8080/register
curl -X POST -d "password=secretsecret&login_token=CRC80JwVDVIEeznVsxfE2CwORohrz7IgoAWSagceQMGZO2bJVTPAYK8LKEIxIg22" localhost:8080/login
curl -H "Authorization: Bearer CRC80JwVDVIEeznVsxfE2CwORohrz7IgoAWSagceQMGZO2bJVTPAYK8LKEIxIg22" -X GET localhost:8080/user
```
