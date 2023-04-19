# 2023 kau 0504   
## 오픈소스 SW 입문      
#      
### 7 주차 : GitHub 2 (Web Page)   

<br/>   

### 참고 페이지(15쪽)
https://www.w3schools.com   
https://developer.mozilla.org/ko

<br/>   

### 새로운 실습용 컨테이너 실행(17쪽)
```sh
docker run -itd --name w7 -p 7070:8080 -v ~/projects:/workspace ubuntu:22.04 bash
```

<br/>  

### 개인 키 파일 모드 수정(19쪽)
```sh
chmod 600 ~/.ssh/id_ed25519

ls -l ~/.ssh/id_ed25519
```

<br/>   

### 컨테이너에 git 사용자 설정(20쪽)
```sh
git --global user.name "<user name>"
git --global user.email <user email address>
```

<br/>   

### 참고자료

무료 ebook :    
[알아서 잘 딱 깔끔하고 센스있게 정리하는 GitHub 핵심개념](https://file.notion.so/f/s/b7bb318d-f15b-4881-bb2e-e7eb7201cc0b/20220324_%EC%95%8C%EC%9E%98%EB%94%B1%EA%B9%94%EC%84%BCGitHub_%EB%B0%B0%ED%8F%AC%EC%9A%A9.pdf?id=2629848c-2d09-47ef-b5dc-823de88c8bf0&table=block&spaceId=579fe283-28aa-489d-ae65-d683304becfc&expirationTimestamp=1681916538176&signature=ps6t5D85IPSf0SwmGa3yfeYqS4nRTOXDr72hJBXM-EU&downloadName=20220324_%EC%95%8C%EC%9E%98%EB%94%B1%EA%B9%94%EC%84%BCGitHub_%EB%B0%B0%ED%8F%AC%EC%9A%A9.pdf)

GitHub cheat sheet :   
[git cheat sheet](https://education.github.com/git-cheat-sheet-education.pdf)