# 내 질문 추적하기
- rust GUI(Floem)
  - [x] (241012업데이트 되어서 해결 되었음. 굿closed 함.)(window-scale) example "windows-scale" is getting an error. It doesn't work on Mac, it doesn't work on Linux. #611   
    - https://github.com/lapce/floem/issues/611
- neovide
  - 실행할때 창크기 지정됨 답변 추가로 달아줌. https://github.com/neovide/neovide/pull/1706

- firefox
  - [x] (맥에서 했으나 동일한 증상)업데이트 이후 선이 너무 굵어지는거 보고함 https://webcompat.com/issues/144593
    - https://github.com/webcompat/web-bugs/issues/144593#issuecomment-2511342606
      - Firefox 133.0.3(64-bi) 버젼업하면서 해결한듯

- 유튜브에서 러스트로 까는거 댓글로 이겨주기 ㅋㅋ
  - [240921C++ vs Rust Speed Comparison | Mial Skywalker](https://youtu.be/t06fisE78TQ?si=F7A5ueqig-RWInEo)

```rs
use std::time::Instant;

fn main() {
    let n = 1000;
    let mat_a = vec![vec![1; n]; n];
    let mat_b = vec![vec![2; n]; n];
    let mut result = vec![vec![0; n]; n];

    let start = Instant::now();

    // Use (chatGPT ^^)
    for i in 0..n {
        for j in 0..n {
            let mut sum = 0;
            for k in 0..n {
                sum += mat_a[i][k] * mat_b[k][j];
            }
            result[i][j] = sum;
        }
    }

    let duration = start.elapsed();
    println!("Multiplication Time: {:.6} seconds", duration.as_secs_f64());
}
```
