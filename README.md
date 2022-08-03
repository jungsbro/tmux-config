# **FolderTree**
```python
# ==============================================================================
.tmux/                          #
    plugins/                    # tmux plugin 폴더
        nord-tmux/              # nord themes
        tmux-continuuum/        # layout 자동 save 및 자동 restore
        tmux-cpu/               # cpu / ram / temp / gpu 사용률
        tmux-prefix-highlight/  # prefix 표시기
        tmux-resurrect/         # layout 저장 (all session, windows, pane)
        tmux-sensible/          # tmux 옵션 집합
        tmux-yank/              # 복사
        tpm/                    # tmux plugin manager
        vim-tmux-navigator/     # vim / tmux 통합 hjkl로 panel 이동
    resurrect/                  # tmux 환경의 작은 세부 사항을 저장
    sidebar/                    # 좌측에 사이드바를 생성
    tmux-powerline/             # tmux 동적인 상태표시줄
# ==============================================================================
.tmux.conf                      "tmux config for ubuntu and debian"
                                # with plugins
# ==============================================================================
.tmux_ct7.conf                  "tmux config for CentOS7"
                                # without pluigns (simple)
# ==============================================================================
.tmux_msys.conf                 "tmux config for msys2"
                                # without pluigns (simple)
# ==============================================================================
```
---
<br><br>



# **Installation**
> tmux installation
```bash
xclip, xsel             # vim, tmux, linux clipboard를 연결
powerline               # powerline plugins
python3-powerline       # python3-powerline plugins
fonts-powerline         # font for powerline
```

```bash
sudo apt install tmux xclip xsel
```

```bash
sudo apt install powerline fonts-powerline python3-powerline
```
<br>

> copying .tmux.conf
1. *.tmux/* 를 ~에 복사
2. *.tmux.conf* 를 ~에 복사
3. *tmux* 실행
<br>
