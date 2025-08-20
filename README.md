# embedded-linux-labs
임베디드 리눅스 학습


repo-root/
├─ README.md                  # 레포 소개 + 목차(핵심 링크만)
├─ docs/                      # 블로그 글(학습 정리) 모음
│  ├─ README.md               # 문서 인덱스(순서 관리 여기서)
│  ├─ kernel-build.md
│  ├─ rootfs-build.md
│  ├─ makefile-practice.md
│  ├─ shell-script-practice.md
│  └─ vim-tips.md
├─ labs/                      # 실습 코드(주제별)
│  ├─ kernel/                 # 커널 관련(결과물 X, 설정/패치만)
│  │  ├─ config/              # .config/defconfig(스냅샷)
│  │  └─ patches/             # 수정사항만 패치로 보관(선택)
│  ├─ rootfs-build/           # rootfs 빌드 스크립트/설정
│  │  ├─ build_rootfs.sh
│  │  └─ notes.md             # 해당 실습 간단 메모(선택)
│  ├─ makefile-practice/      # Makefile 실습 모음
│  │  ├─ ex01_hello/Makefile
│  │  └─ ex02_pattern-rules/Makefile
│  ├─ shell-scripts/          # 쉘스크립트 연습
│  │  ├─ find_empty_dirs.sh
│  │  └─ backup_home.sh
│  └─ vim-test/               # vim 연습(필요시)
│     └─ sample.c
├─ assets/                    # 스크린샷/로그(증거자료)
│  ├─ kernel_build_dmesg.txt
│  ├─ qemu_boot.png
│  └─ rootfs_tree.png
├─ scripts/                   # 공용 보조 스크립트(문서 생성/로그 캡처 등)
│  ├─ new_doc.sh              # docs 스캐폴드
│  └─ capture_logs.sh         # dmesg/lsmod 캡처
└─ .gitignore
