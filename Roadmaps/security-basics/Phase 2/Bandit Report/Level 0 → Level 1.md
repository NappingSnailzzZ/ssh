# OverTheWire Bandit

# Level 0 → Level 1

### 문제 정보
- **목표**: 홈 디렉토리에 있는 readme 파일에서 다음 레벨의 비밀번호를 찾기
- **현재 비밀번호**: bandit0

### 풀이 과정

#### 1. 상황 파악
bandit0에 접속한 후, ls 명령어로 홈 디렉토리에 어떤 파일이 있는지 확인했다.

```bash
bandit0@bandit:~$ ls
readme
```

#### 2. 시행착오
이 레벨에서는 별다른 시행착오 없이 해결했다.

#### 3. 해결
readme 파일의 내용을 읽어 비밀번호를 확인했다.

```bash
bandit0@bandit:~$ cat readme
The password you are looking for is: ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
```

#### * 발견한 비밀번호
`ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If`


### 새로 알게 된 명령어
| 명령어 | 설명 | 사용 예시 |
|---|---|---|
| `ls` | 현재 디렉토리의 파일 목록을 출력 | `ls` |
| `cat` | 파일의 내용을 화면에 출력 | `cat readme` |

### Level 정리
`ls`로 파일 목록을 확인하고, `cat`으로 파일 내용을 읽는 가장 기본적인 리눅스 명령어 사용법을 익혔다.