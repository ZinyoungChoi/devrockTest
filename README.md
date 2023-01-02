# devrock-homepage

# How To Use

    1. AWS CLI 설치

        : https://docs.aws.amazon.com/ko_kr/cli/latest/userguide/install-cliv2.html


    2. AWS Configure

        : 프로젝트 루트 디렉토리에서 aws configure --profile devrock-homepage 입력 (개인 계정 key)

        ```

        AWS Access Key ID [****************27F3]: ${Access Key 값 입력}

        AWS Secret Access Key [****************GKWj] : ${Secret Access Key 값 입력}

        Default region name [ap-northeast-2] : ap-northeast-2

        Default output format [json] : json

        ```


    3. AWS S3 SYNC (배포)

       aws s3 sync ./ s3://devrock-homepage-static/ --profile devrock-homepage
