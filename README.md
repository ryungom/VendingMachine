# ๐ฅคVendingMachine_making
![์์ฑํ์ด์ง](https://github.com/ryungom/VendingMachine/blob/main/images/view.gif)
- [์์ฑํ์ด์ง ๋ณด๋ฌ๊ฐ๊ธฐ](https://ryungom.github.io/VendingMachine/)

## โ๏ธissue list
- 22.04.13
  - html,css๋ฅผ ์ด์ฉํ์ฌ ์ต๋ํ ๋น์ทํ๊ฒ ์์ฑ. ๊ทธ๋ฌ๋ ๋ฑ ํ๊ตฐ๋ฐ, ๋ณด๋ผ์ ์ฝ๋ผ์์ ๊ฒ์ ๋ฐฐ๊ฒฝ์ผ๋ก ํฌ๋ช๋ 80์ ๋๋ก 'ํ์ '๋ก๊ณ  ๋์ฐ๊ธฐ ์คํจ.
  - z-index๋ฅผ ์ฌ์ฉํ๋ฉด ๋ ๊ฒ๊ฐ๊ธดํ๋ฐ... ์๋จนํ๋ค
- 22.04.19
  - ๋ณด๋ผ์ ์ฝ๋ผ ์ ๊ฒ์ ๋ฐฐ๊ฒฝ์ผ๋ก 'ํ์ '๋ก๊ณ  ๋์ฐ๊ธฐ ์ฑ๊ณต. ์์ธ์ ๊ฐ์์์์ content:'';์ ๋ฃ์ด์ฃผ์ง ์์์, ์ปจํ์ธ ๊ฐ ์๋๊ฒ์ผ๋ก ์ธ์.
  - ์ ์ฒด ํฐ ๋ ์ด์์๋ค์ height์์๋ฅผ ์ ๊ฑฐํ๊ณ  ์์์์๋ค์ด ์๋๋งํผ ๋์ด๋ฅผ ์์ฑํ  ์ ์๋๋ก ํ์๋ค.
  - ๊ฐ์ํด๋์ค์ ์์ ์์์ ์์น์ ๊ทผ๋ณธ์ด ๋๋ position:relative;๋ฅผ ๋ฃ์ด์ฃผ๊ณ , ํด๋น์์์ position:absolute;๋ฅผ ๋ฃ๊ณ  z-index๋ฅผ ๋ฃ์ด์ ์์ ํ ๋์ ๋ค.
    - ๊ทธ๋ฐ๊ณ ๋ก, ํ์ ์์ ๋ํ๋ด๊ธฐ ์ฑ๊ณต!๐
  - ๋ฐ์ํ ๋ฏธ๋์ด ์ฟผ๋ฆฌ ์์ ๋ฃ๊ธฐ ์ฑ๊ณต!! ์ ์ฒด๋ฅผ ๊ฐ์ธ๋ main์ flex๋ฅผ ๋ฃ๊ณ  ๋ฐฉํฅ์ column, ์์ ์ ๋ ฌ์ center์ ์ฃผ์ด 748px(์ ์ฒด width)๋ณด๋ค ํ๋ฉด์ด ์ค์ด๋ค๋ฉด ์๋๋ฐฉํฅ์ผ๋ก display๊ฐ ์ถ๋ ฅ ๋๋๋ก ์์ ํ์๋ค.
  - ์ผ์ชฝ์์(.list)์ ์ค๋ฅธ์ชฝ์์(.result)์ float์ none์ผ๋ก ์ฃผ์ด ๋ธ๋ฉflow์ ๊ทธ๋๋ก ์์ฐฉ๋์ด ์์์์์ธ main์ด flex๋ก ํ์์์๋ค์ ์ปจํธ๋กค ํ  ์ ์๋๋ก ๋ฐ๊พธ์๋ค.
  - ์ผ์ถ ํผ๋๋ฐฑ์ ๋ฐ์ ํ, JS์์๋ฅผ ์ถ๊ฐํ์ฌ ์ง์ ํ vendingMachine์ด ๋  ์ ์๋๋ก ์กฐ์ ํด๋ด์ผ ํ ๋ฏ ํ๋ค.
  - class๋ช ์๋ช์ ์์ง ์๋๋ ๋ด์ง ๋ชปํ์๋ค. ๋ณด๋ค ์ง๊ด์ ์ธ class๋ช์ด ๋  ์ ์๋๋ก ์งํํ๊ธฐ.
- 22.05.01
  - 'ํ์ '์์์ ์ค์๋ฐฐ์น๊ฐ ์ด๊ธ๋์๋๊ฒ์ ๋ฐ๊ฒฌํด์ ์๋กญ๊ฒ ์์ ์๋ฃ. js๋ถ๋ถ ์ ์ธํ๊ณ  `๋งํฌ์ 100%` ์๋ฃ.
