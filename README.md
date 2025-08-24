# installation

## Mac OS X

### Just set it up

잘 알든 모르든 일단 설치하고 보는 도구들.

* https://www.firefox.com/
* https://karabiner-elements.pqrs.org
* https://wezterm.org/

### Requires Long Time

* `sudo xcode-select --install`
  * homebrew 랑 command-line tool 이랑 git 충돌은 없나...?
  * Local NAS 에 구 버전 설치파일이라도 옮겨둘까?

### 그 이후에 설치 가능한 것들

Apple 에서 제공하는 공식 Git 바이너리를 XCode command-line tools 에서 한 차례 얻고, 이 후에 homebrew 로 git 을 설치하는 방식이 그나마 괜찮아 보임.

* https://brew.sh
* https://ohmyz.sh

### 공부중

익숙해져야 할 거 같은데 아직 잘 모르는 도구들.

* https://github.com/astral-sh/uv
  * `uv python install 3.12.11` 후 `uv init` 하고 `uv add jupyter`, `uv run jupyter notebook` 하니 뭔가 익숙한 상황이 나오는 듯. 
* https://github.com/abiosoft/colima
  * 개인용으로는 Orbstack 이 좀더 낫다고 하는데, Orbstack 을 쓸 경우 상업용으로는 라이센스 비용이 발생하는 듯.
* Rosetta 2
  * https://www.reddit.com/r/MacOS/comments/rq89is/comment/i2zwy07/
  * iTerm2 같은 Universal App 을 다운받고, Get Info 에서 "Open in Rosetta" 설정하여 Rosetta 2 설치를 하면 되는 듯?
