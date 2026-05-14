# 🛠 실습 과제: "Antigravity 환경 준비하기"

이론만 보면 금방 잊어버립니다. 아래 과정을 터미널에서 직접 수행하며 첫 발을 떼보세요!

## 📋 과제 순서

### 1. 실습 폴더 생성 및 이동
`practice/` 폴더 안으로 이동하여 `learning_linux`라는 폴더를 만듭니다.
```bash
cd practice
mkdir learning_linux
cd learning_linux
```

### 2. 파일 생성 및 내용 입력
`test.txt`라는 파일을 만들고 "Hello Linux"라는 내용을 넣습니다.
```bash
echo "Hello Linux" > test.txt
```

### 3. 파일 복사
`test.txt`를 `backup.txt`로 복사합니다.
```bash
cp test.txt backup.txt
```

### 4. 이름 변경 및 권한 수정
`backup.txt`를 `readonly.txt`로 이름을 바꾸고, 본인만 읽을 수 있게 권한을 400으로 수정합니다.
```bash
mv backup.txt readonly.txt
chmod 400 readonly.txt
```

### 5. 프로세스 확인
실행 중인 프로세스 목록에서 현재 쓰고 있는 셸(bash나 zsh 등)을 찾아보세요.
```bash
ps -ef | grep $SHELL
```

---

## ✅ 완료했다면?
위 과정을 모두 마쳤다면, 이제 **Step 1**부터 하나씩 차례대로 학습을 진행해 보세요!
궁금한 점이 있다면 언제든 저에게 질문해 주세요. 🚀
