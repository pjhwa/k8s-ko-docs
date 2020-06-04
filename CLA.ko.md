# 기여자 라이선스 계약

[클라우드 네이티브 컴퓨팅 파운데이션](https://www.cncf.io/community)(CNCF)은
[개별 기여자](https://github.com/cncf/cla/blob/master/individual-cla.pdf)와 [회사](https://github.com/cncf/cla/blob/master/corporate-cla.pdf)의
두 가지 다른 유형의 CLA(_기여자 라이선스 계약(Contributor License Agreement)_)에서 기여한 코드의 법적 상태를 정의한다.

쿠버네티스는 CLA 서명자의 원본 소스 코드만 허용한다.

이 정책은 [써드파티](https://git.k8s.io/kubernetes/third_party)와
[공급 업체](https://git.k8s.io/kubernetes/vendor)에는 적용되지 않는다.

이 법적 계약을 읽고 이해하는 것이 중요하다.

## 어떻게 서명하나?

작업이 회사의 직원으로 수행되는 경우, 회사의 법무 부서에 연락하여 CNCF CLA의 승인된 기여자 목록을 요청한다. 아래에 여러분의 회사에 회사 계약이 없고 계약을 맺고자하는 경우를 위한 "법인 가입" 단계가 포함되어 있다.

#### 1. Github을 사용하여 Linux Foundation ID 포털에 로그인

다음 중 하나를 클릭한다.
  * 개인이나 서명된 조직의 직원으로 가입하기 위한
  [개인 가입](https://identity.linuxfoundation.org/projects/cncf).
  * 법인 대표로 등록하고 조직의 가입을 관리하기 위한
  [법인 가입](https://identity.linuxfoundation.org/node/285/organization-signup).
  
로그인 화면이 나오면, "Github으로 로그인"을 클릭한다.

![CNCFCLA1](http://i.imgur.com/tEk2x3j.png)

#### 2. 정확한 이메일 주소로 Linux Foundation ID 포털 계정 생성

이 양식을 작성할 때 사용하는 이메일 주소가
커밋에 사용할 이메일 주소와 일치하는지 확인한다.

직원으로 가입하는 경우, CNCF 계정 등록 페이지에서 공식
person@organization.domain 이메일 주소를 사용해야 한다.

![CNCFCLA2](http://i.imgur.com/t3WAtrz.png)

#### 3. 서명 절차 완료

계정을 생성한 후, 지침에 따라 HelloSign을 통해
서명 프로세스를 완료한다.

HelloSign으로부터 이메일을 받지 못했다면, [여기로 요청한다](https://identity.linuxfoundation.org/projects/cncf).

#### 4. Github 이메일 주소가 CLA 서명에 사용된 주소와 일치하는지 확인

Github 이메일 주소는 CLA에 서명할 때 사용하는 것과 동일한 주소로
__반드시 일치해야 한다__. Github에는 이메일 주소 설정에 대한
[문서](https://help.github.com/articles/setting-your-commit-email-address-on-github/)가 있다.

또한 [git 이메일](https://help.github.com/articles/setting-your-email-in-git)도
이 이메일 주소와 일치하도록 설정해야 한다.

이미 PR을 제출했다면 user.name과 user.email을 정정한 다음
`git commit --amend --reset-author`를 사용하고 `git push --force`를 사용하여
PR을 정정할 수 있다.

#### 5. 성공적인 가입을 알리는 이메일을 찾는다.

> The Linux Foundation
>
> Hello,
>
> You have signed CNCF Individual Contributor License Agreement.
> You can see your document anytime by clicking View on HelloSign.
>

이 메일을 받았다면 CLA 인증 봇이 PR을 승인한다.

![CNCFCLA3](http://i.imgur.com/C5ZsNN6.png)

## 소속 변경

회사를 옮긴 이후에도 여전히 쿠버네티스에 기여하는 경우, 소속을
업데이트해야 한다. 클라우드 네이티브 컴퓨팅 파운데이션(CNCF)은 [gitdm](https://github.com/cncf/gitdm)을 사용하여
누가 기여하고 있고 어디에 소속되어 있는지 추적한다. 해당 개발자 소속 텍스트 파일을 변경하여
[gitdm](https://github.com/cncf/gitdm) 리포지터리에서 풀 리퀘스트을 작성한다.
입력한 내용은 다음과 유사해야 한다.

```
Jorge O. Castro*: jorge!heptio.com, jorge!ubuntu.com, jorge.castro!gmail.com
Heptio
Canonical until 2017-03-31
```

## 문제 해결

CLA 서명에 문제가 발생하면, [Linux Foundation 지원 사이트]를 통해
Linux Foundation ID 그룹에 티켓을 기록한다.

LF 지원 사이트 사용에 문제가 있는 경우, 백업 이메일 지원 주소인
<login-issues@jira.linuxfoundation.org> 로 메시지를 보낸다.

CNCF의 누군가가 당신의 티켓에 도움을 줄 것이다.

## CNCF CLA 검사 설정

쿠버네티스 GitHub 조직이나 리포지터리 소유자이고
리포지터리에 Linux Foundation CNCF CLA 검사를 설정하려면, [CNCF CLA 검사 설정에 대한 문서를 읽어본다](/github-management/setting-up-cla-check.md).


[Linux Foundation 지원 사이트]: https://support.linuxfoundation.org/
