# my_Contributions

<p align="center">
  <img alt="rust1" width=60px src="https://user-images.githubusercontent.com/67513038/213436632-820a1675-98d9-4626-979d-be63c60cdcb7.png" />
  <img alt="ferris" width=30px src="https://user-images.githubusercontent.com/67513038/213403213-1b1b3efc-ce53-4825-9dfc-e9bf2956a7f4.svg" />
</p>

<hr>

# Rust 컴파일에 기여하는 방법
- https://rustc-dev-guide.rust-lang.org/contributing.html#writing-documentation

# Code Contributions

- sdl3-rs
  - https://github.com/vhspace/sdl3-rs/graphs/contributors
  - YoungHaKim7
  - 기여함

- zed
  - zed(crate중 gpui 예시 자료가 무한루프에 빠져서 잘 종료 되지 않는거 코드기여함)
    - https://github.com/zed-industries/zed/pull/26701 

- 내가 만든 러스트 라이브러리(crates.io)
  - 3자리 숫자마다 콤마(,) 찍어주는 api(돈 표시 눈에 잘보이기 하기)
    - https://crates.io/crates/fprice
      - 2번째 버젼
        - https://crates.io/crates/fprice2
  - 컴퓨터 시계만으로 우리나라 및 다른 나라 시간 구현하기
    - https://crates.io/crates/com_local_time

<hr />

- 옛날 러스트 코드 현재버젼으로 업그레이드중
  - Rust1.82에 되는 rtail
    - [x] https://github.com/YoungHaKim7/rtail
  
- 다른 사람이 만들거 한번 더 연습
  - curl을 러스트 코드로
    - [x] https://github.com/YoungHaKim7/rurl

<hr />

- examples(Rust)
  - SDL3
    - [x] 예문 삼각형 만들기 추가 https://github.com/revmischa/sdl3-rs/pull/56 
    - [x] renderer시리즈 시작(예재2개) 있음. https://github.com/revmischa/sdl3-rs/pull/63 
    - [x] renderer시리즈(10개 추가) https://github.com/revmischa/sdl3-rs/pull/70
    - [ ] sdl3-sys 업데이트 문제로 이상 불가능함
      - [ ] [sdl3-sys 기여해야함](https://github.com/maia-s/sdl3-sys-rs/tree/main/sdl3-main).. 점점 난이도 올라간다 ㅜㅜ
 
  - persus
    - [ ] tailwindcss - plugins (Add Examples) #301(tailwindcss는 상업용이라 빠꾸 먹음 ㅋㅋ)
      - https://github.com/framesurge/perseus/pull/301


  - macroquad-text
    - [ ] Kr example Add #5
      - https://github.com/Ricky12Awesome/macroquad-text/pull/5

<hr>

- code fix(Rust)
  - iced(Rust)
    - [ ] example__ visible_bounds_fix #2118 (내가 실수한거임. ㅠㅠ)
      - https://github.com/iced-rs/iced/pull/2118  

<hr>

# Issues Contributions(bug reports)
- zed(Rust)
  - [x] [vim] I usually use ctrl-y when I do autocomplete on Neovim, but I don't think it's possible to do it on zed. #8707
    - https://github.com/zed-industries/zed/issues/8707
  
  - [x] [vim] I set it to do escape when I press jk, but it doesn't work when I press jk during auto completion. #8729
    - https://github.com/zed-industries/zed/issues/8729

- shuttle(Rust)
  - [x] [Bug]: cargo shuttle run(openssl-sys) does not detect the correct path for the cargo executable #1103 
    - https://github.com/shuttle-hq/shuttle/issues/1103

- Rust Bevy Game Engine
  - Helix키(Vim키로 세팅하고 쓰는법)
    - https://github.com/bevy-cheatbook/bevy-cheatbook/issues/232 

# StackOverFlow 질문 답변

- (240310)정확하지는 않지만 일단 제출(된게 어디냐...)
  - https://stackoverflow.com/questions/63737115/im-having-difficulty-understanding-how-to-implement-a-task-scheduler-using-cros/78136260#78136260

- (240505)Fn & FnMut & FnOnce(활용법)
  - https://stackoverflow.com/questions/66788842/storing-the-return-value-from-an-fn-closure/78431065#78431065

- (240505)Convenient way to transform struct with Cow-fields to owned
  - https://stackoverflow.com/questions/42155212/convenient-way-to-transform-struct-with-cow-fields-to-owned/78431757#78431757
 
- (240505)How to manipulate an instance of a mutable struct in Rust - ownership woes
  - https://stackoverflow.com/questions/71444348/how-to-manipulate-an-instance-of-a-mutable-struct-in-rust-ownership-woes/78431834#78431834

- (240505답변 만족 스럽지 않아 삭제함-더 공부하자(x)How can I ensure that generic argument types are different?(x)
  - https://stackoverflow.com/questions/78431709/how-can-i-ensure-that-generic-argument-types-are-different/78432024#78432024

# Rust Tutorial 제작중.
- Rust_Game_Dev
  - (영상모아보기) https://youtube.com/playlist?list=PLcMveqN_07mY5cEcTgC4ICHnla6LSVtnh&si=VDjZDqS2JUDTwfIe
    - github https://github.com/YoungHaKim7/Rust_Bevy_Game_Engine
- Rust Leptos(WASM) Tutorial
  - (영상모아보기) [Rust_Leptos기초_Tutorial](https://youtube.com/playlist?list=PLcMveqN_07ma1Wv7pWF02UURgLjew97ZC&si=uuVsvn3fYxpYe22A)
    - github code https://github.com/YoungHaKim7/Rust_Leptos_FullStack
- Rust_C++_Vulkan
  - (영상모아보기) [Rust_C++_Vulkan](https://youtube.com/playlist?list=PLcMveqN_07mYLlQ72z9uktIcWF0kNLGxB&si=IGQWHOVAcwWxj803) 

- Rust_GUI
  - (영상모아보기) [Rust_GUI](https://youtube.com/playlist?list=PLcMveqN_07maE4SmyCX5v_QUZami6Pm6t&si=tUyWjXcfmWKzskLG)

- Rust총정리
  - https://younghakim7.github.io/rust_kr/
