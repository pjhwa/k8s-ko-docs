# Contributor License Agreement (CLA)

모든 쿠버네티스 기여자는 반드시 '기여자 가이드'를 읽고 '기여자 라이선스 계약(CLA)에 서명해야 합니다.
CLA에 서명하지 않은 기여자의 풀 리퀘스트(pull request)는 자동 테스트에 실패하며, 서명 전까지는 리뷰 절차가 진행되지 않습니다.

* [기여자 가이드](https://github.com/kubernetes/community/blob/master/contributors/guide/README.md)
* [기여자 라이선스 계약(CLA)에 서명(원문)](https://github.com/kubernetes/community/blob/master/CLA.md)
* [기여자 라이선스 계약(CLA)에 서명(한글)](https://github.com/pjhwa/k8s-ko-docs/blob/master/CLA.ko.md)

## CLA 서명

CLA 서명 시 사용하는 이메일 주소는 모두 동일해야 합니다. (Github.com, Linux Foundation, CNCF, 로컬 PC의 git 설정)

- https://github.com/<username>
- https://identity.linuxfoundation.org/projects/cncf
- https://github.com/cncf/gitdm
- ```git config --global user.email "user@email.com"```

만일 PR을 이미 제출하였다면, 아래의 단계로 PR을 수정할 수 있습니다.

1. `user.name`와 `user.email`을 수정
2. `git commit --amend --reset-author` 실행
3. `git push --force` 실행

### GitHub의 이메일 설정

GitHub의 설정에서 이메일이 아래와 같이 설정되어야 합니다.

- Settings -> Emails -> Primary email address
- Settings -> Emails -> Visible in emails (위의 Primary email address에 대해서 설정됨을 확인)

예를 들면, 아래의 그림과 같습니다.

![image](https://user-images.githubusercontent.com/2810001/100183405-2f117980-2f22-11eb-9950-b68367eb7994.png)
