# BMI Calculator

這是一個使用 [Create React App](https://create-react-app.dev/) 製作的練習專案，功能為計算 BMI（Body Mass Index）並保存歷史紀錄。

## 目錄

- [專案介紹](#專案介紹)
- [功能說明](#功能說明)
- [安裝與使用](#安裝與使用)
- [專案結構](#專案結構)
- [貢獻指南](#貢獻指南)
- [License](#license)

## 專案介紹

BMI 計算器是一個簡單的 React 應用，讓使用者可以輸入身高和體重來計算 BMI 值，並將結果保存至歷史紀錄中。

## 功能說明

- **BMI 計算**：使用者可以輸入身高（公尺）和體重（公斤），並計算出對應的 BMI 值。
- **歷史紀錄**：每次計算的結果將會保存至歷史紀錄列表中，使用者可以瀏覽過去的計算結果。

## 安裝與使用

1. **克隆這個倉庫**

   ```sh
   git clone https://github.com/your-username/bmi-calculator.git
   cd bmi-calculator
   ```

2. **安裝依賴**

   使用 npm:

   ```sh
   npm install
   ```

   或者使用 yarn:

   ```sh
   yarn install
   ```

3. **運行應用**

   使用 npm:

   ```sh
   npm start
   ```

   或者使用 yarn:

   ```sh
   yarn start
   ```

   在瀏覽器中打開 [http://localhost:3000](http://localhost:3000) 來查看應用。

## 專案結構

```plaintext
bmi-calculator/
├── public/
│   ├── index.html
│   └── ...
├── src/
│   ├── components/
│   │   ├── BmiCalculator.js
│   │   ├── History.js
│   │   └── ...
│   ├── App.js
│   ├── index.js
│   └── ...
├── .gitignore
├── package.json
├── README.md
└── ...
```

## 貢獻指南

歡迎任何人來貢獻此專案！如果你有任何建議或改進，請隨時提交 pull request。

1. Fork 這個倉庫
2. 建立一個新分支 (`git checkout -b feature/your-feature`)
3. 提交你的更改 (`git commit -m 'Add some feature'`)
4. 推送到分支 (`git push origin feature/your-feature`)
5. 打開一個 Pull Request

## License

本專案不包含任何版權，任何人都可以自由使用、修改及分發。
