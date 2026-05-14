# Step 2. 파일과 폴더 주무르기

구글링으로 그때그때 찾아 쓰던 명령어들의 옵션을 명확히 정리할 차례입니다.

## 📁 주요 명령어

### 1. `mkdir` (Make Directory)
- **용도**: 폴더 생성
- **옵션**: `mkdir -p path/to/folder` (하위 폴더까지 한 번에 만들기)

### 2. `cp` (Copy)
- **용도**: 파일 또는 폴더 복사
- **옵션**: `cp -r [source] [dest]` (폴더 전체를 복사할 때는 반드시 `-r` recursive 옵션이 필요합니다.)

### 3. `mv` (Move)
- **용도**: 이동 및 이름 바꾸기
- **설명**: 이동뿐만 아니라 '이름 바꾸기'도 이 명령어로 수행합니다.
    - 예: `mv old_name new_name`

### 4. `rm` (Remove)
- **용도**: 삭제 (매우 신중해야 함!)
- **옵션**: `rm -rf [target]` (묻지도 따지지도 않고 삭제하라는 뜻입니다. 신중히 사용하세요.)

---

## 🏃 연습해보기
1. `mkdir practice_folder`를 입력해 폴더를 만들어 보세요.
2. `touch test.txt`로 빈 파일을 만들고 `cp test.txt test_copy.txt`로 복사해 보세요.
3. `mv test_copy.txt renamed.txt`로 이름을 바꿔 보세요.
4. `rm renamed.txt`로 파일을 삭제해 보세요.
