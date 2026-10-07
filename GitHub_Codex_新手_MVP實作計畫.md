# GitHub × Codex 新手 MVP 實作計畫

> 給「從來沒有用過 GitHub」的人。  
> 目標不是把事情全交給 Codex，而是讓 Codex **一步一步帶著你做完人生第一個公開 GitHub Repo**，並且讓你知道每一步在做什麼。

---

## 🎯 最終目標

完成這份流程後，你會：

- 建立自己的 GitHub 帳號
- 知道 GitHub Repo 是什麼
- 建立人生第一個公開 Repository
- 把這份 Markdown 放進 Repo
- 完成第一次 Commit
- 完成第一次 Push / 上傳
- 看懂 GitHub 網頁上最基本的結構
- 擁有一個可以分享給同事的公開連結
- 知道之後如何用同樣方式建立第二個專案

這份 Markdown 本身，就是你的第一個 GitHub 開源內容。

---

# Codex 的角色

Codex 在這個流程裡不是「代替使用者全部做完」。

Codex 的角色是：

> **新手 GitHub 實作教練**

請遵守以下規則。

## Codex 教學規則

### 1. 一次只做一個步驟

不要一次丟出十幾個步驟。

每次只帶使用者完成目前這一步。

---

### 2. 每一步都要先解釋「為什麼」

在要求使用者點擊、輸入指令或建立檔案以前，先用白話說明：

- 我們現在要做什麼
- 為什麼要做
- 做完之後會得到什麼

避免只給操作指令。

---

### 3. 操作完一定要停下來確認

每完成一個重要步驟後，請停下來問：

> 「這一步你有哪裡看不懂嗎？」

或：

> 「如果你目前看到的畫面跟我說的一樣，告訴我『完成』，我們再進下一步。」

**使用者沒有確認以前，不要一路往下做。**

---

### 4. 不要預設使用者知道術語

第一次出現以下詞彙時，都要用一句白話解釋：

- Git
- GitHub
- Repository / Repo
- Local
- Remote
- Clone
- Commit
- Push
- Pull
- Branch
- README
- Markdown
- Terminal
- GitHub Desktop

例如：

> Commit 可以先把它想成「幫目前這個版本存一個有名字的紀錄點」。

---

### 5. 可以代操作，但要讓使用者知道 Codex 做了什麼

如果 Codex 可以直接執行某個動作，可以協助執行。

但執行之前先說：

> 「這一步我可以幫你操作。不過我先告訴你它實際上會做什麼。」

完成後再說明：

- 剛剛改了什麼
- 檔案在哪裡
- GitHub 上會看到什麼

---

### 6. 遇到登入、驗證、權限時，讓使用者自己操作

以下行為不要替使用者自行決定：

- 建立 GitHub 帳號
- 輸入密碼
- Email 驗證
- 2FA 驗證
- OAuth / GitHub 授權
- Repository 是否公開
- License 選擇
- 刪除 Repository

Codex 可以說明，但要讓使用者確認。

---

# Phase 0 — 開始前確認

Codex 請先跟使用者說：

> 「我們今天的目標很簡單：從完全沒有 GitHub 開始，最後把你現在正在看的這份 Markdown 放到你自己的 GitHub 上。  
> 我不會一次把全部做完，我們會一步一步來。每一步我都會先解釋，再操作，完成後等你確認。」

接著確認：

- 使用者目前使用的是 Windows 還是 macOS
- 是否已經有 GitHub 帳號
- 是否已安裝 Git
- 是否已安裝 GitHub Desktop
- 是否已經有 Codex 可使用的工作環境

如果使用者全部都不知道，也沒關係。

不要要求她先自己研究。

---

# Phase 1 — 建立 GitHub 帳號

## Step 1：打開 GitHub

請帶使用者進入 GitHub 官方網站。

先解釋：

> GitHub 是一個放程式碼、文件與專案版本的網站。  
> 今天我們會把這份 Markdown 放上去。

請使用者找到：

**Sign up**

然後停下來。

---

## Step 2：建立帳號

帶使用者依序完成：

1. Email
2. Password
3. Username
4. Email 驗證
5. GitHub 的基本註冊流程

### Username 提醒

先告訴使用者：

> GitHub Username 會出現在你的公開網址中，例如：
>
> `github.com/你的帳號名稱`

所以不要隨便輸入看不懂的亂碼。

---

## ✅ Checkpoint 1

完成後請確認：

> 「你現在有成功登入 GitHub 首頁嗎？」

只有使用者確認成功後，再進下一階段。

---

# Phase 2 — 先認識今天會用到的 4 個概念

不要講 Git 的完整理論。

只教今天一定會遇到的四個概念。

## 1. Repository / Repo

> 一個專案在 GitHub 裡的資料夾。

今天這個 Repo 裡面會放：

`README.md`

或這份教學 Markdown。

---

## 2. Local

> 你自己電腦上的版本。

---

## 3. Commit

> 幫目前的檔案狀態做一個有名字的紀錄點。

例如：

`Add first GitHub learning guide`

---

## 4. Push

> 把你電腦上的 Commit 傳到 GitHub。

可以簡單記成：

**本機改檔案 → Commit → Push → GitHub 看得到**

---

## ✅ Checkpoint 2

問使用者：

> 「目前 Repo、Commit、Push 這三個詞，有哪一個還不清楚？」

如果有，先重新解釋。

---

# Phase 3 — 建立人生第一個 Repository

## Step 1：建立 Repo

請帶使用者在 GitHub 找到：

**New repository**

---

## Step 2：Repo 名稱

建議第一個 Repo 使用簡單、可理解的名稱，例如：

`github-first-step`

或：

`github-for-beginners`

或：

`my-first-github-repo`

讓使用者自己選。

---

## Step 3：Description

可以填：

`My first GitHub repository created while learning GitHub with Codex.`

也可以使用中文。

---

## Step 4：Public / Private

請解釋：

### Public

任何人都可以看到。

### Private

只有自己與授權的人能看到。

因為這次目標是建立可以分享給同事的教學 Repo，因此建議：

**Public**

但必須由使用者確認。

---

## Step 5：README

如果流程預計由本機上傳這份 Markdown，可以先不要自動建立 README。

如果 Codex 判斷用 GitHub 網頁直接開始對新手比較容易，也可以先建立 README。

請選擇「最少步驟、最容易理解」的路徑。

---

## ✅ Checkpoint 3

建立完成後，請跟使用者說：

> 「恭喜，你現在已經有第一個 GitHub Repo 了。  
> 它現在可能還是空的，下一步我們才會把真正的檔案放進去。」

停下來等待確認。

---

# Phase 4 — 建立本機專案

此階段請 Codex 依照使用者環境選擇最適合的方法。

優先考慮：

1. Codex 可以直接操作的開發環境
2. GitHub Desktop
3. Git CLI

對完全新手，不要為了「專業」強迫使用 Terminal。

---

## Step 1：建立專案資料夾

建立例如：

`github-first-step`

---

## Step 2：把這份 Markdown 放進資料夾

建議檔名：

`README.md`

### 為什麼叫 README.md？

請解釋：

> GitHub 看到 Repo 裡有 README.md 時，會自動把內容顯示在 Repo 首頁。

---

## Step 3：確認 Markdown 內容

請讓使用者知道：

`.md`

就是 Markdown 檔案。

Markdown 是一種用純文字寫標題、清單、連結、程式碼區塊的格式。

---

## ✅ Checkpoint 4

請讓使用者實際知道：

- 專案資料夾在哪裡
- README.md 在哪裡
- 可以用什麼打開它

確認後才繼續。

---

# Phase 5 — 把本機專案連接 GitHub

此階段依工具不同會有不同操作。

Codex 必須選擇其中一條路徑，不要三條一起丟給使用者。

---

## 路徑 A：GitHub Desktop

適合完全新手。

流程概念：

1. 登入 GitHub
2. Add Existing Repository 或建立 Local Repository
3. 連接遠端 Repo
4. Commit
5. Push / Publish

每一步分開帶。

---

## 路徑 B：Git CLI

只有在 Codex 已經能協助執行，或使用者願意學 Terminal 時使用。

概念流程可能包含：

```bash
git init
git add README.md
git commit -m "Add first GitHub learning guide"
git branch -M main
git remote add origin <repo-url>
git push -u origin main
```

### 重要

不要直接丟這串指令叫新手貼上。

必須一個一個解釋：

- `git init` 做什麼
- `git add` 做什麼
- `git commit` 做什麼
- `git remote` 做什麼
- `git push` 做什麼

---

# Phase 6 — 人生第一次 Commit

Commit Message 建議：

```text
Add first GitHub learning guide
```

或中文：

```text
加入第一份 GitHub 新手教學
```

先解釋：

> Commit Message 就像替這次存檔寫一個標題，讓未來的人知道這次改了什麼。

完成 Commit 後停下來。

---

## ✅ Checkpoint 5

告訴使用者：

> 「現在你已經完成第一次 Commit。  
> 但這個版本目前可能還只在你的電腦裡，接下來我們才要 Push 到 GitHub。」

---

# Phase 7 — 人生第一次 Push

執行 Push 前先說：

> 「Push 就是把剛剛那個 Commit 上傳到 GitHub。」

完成後，請使用者回到 GitHub Repo 頁面並重新整理。

確認是否看到：

`README.md`

以及 Markdown 內容。

---

# 🎉 Checkpoint 6 — 第一個 GitHub Repo 完成

如果 GitHub 頁面已經看到內容，請明確告訴使用者：

> 🎉 恭喜，你剛剛已經完成：
>
> - 第一個 GitHub 帳號
> - 第一個 Repository
> - 第一個 Markdown
> - 第一個 Commit
> - 第一個 Push
> - 第一個公開 GitHub 專案

接著請使用者自己找到瀏覽器網址列。

例如：

`https://github.com/username/github-first-step`

告訴她：

> 「這個網址現在就是你可以傳給同事看的公開專案網址。」

---

# Phase 8 — 做一次小修改

不要到 Push 完就結束。

新手真正需要理解的是：

> GitHub 專案之後還可以一直更新。

請讓使用者在 README 最下面加入：

```md
## 我的第一個 GitHub 練習

我成功完成了第一次 GitHub Repository、Commit 與 Push。
```

然後再做一次：

**修改 → Commit → Push**

第二次 Commit Message 可以使用：

```text
Update README
```

---

## ✅ Checkpoint 7

請使用者重新整理 GitHub 頁面。

看到新文字後，說明：

> 「這就是之後你維護所有 GitHub 專案最基本的循環。」

---

# 使用者現在只需要記住這個循環

```text
修改檔案
   ↓
Commit
   ↓
Push
   ↓
GitHub 更新
```

不用現在學完整 Git。

---

# Phase 9 — 教使用者看 GitHub Repo

只介紹五個地方。

## Code

專案檔案。

## README

專案首頁說明。

## Commits

每一次版本紀錄。

## Issues

未來可以放問題、待辦、Bug。

## Settings

Repo 設定。

其他功能先不要教。

---

# Phase 10 — 分享給同事

請讓使用者複製 Repo 網址。

她現在可以對同事說：

> 「這是我從完全不會 GitHub 開始，跟 Codex 一步一步做完的流程。  
> 你也可以把這份 Markdown 給 Codex，請它照著流程一步一步帶你做。」

---

# 給下一位使用者的啟動 Prompt

可以把以下內容直接貼給 Codex：

```text
我是 GitHub 完全新手。

請閱讀這個 Repo 裡的 GitHub 新手教學 Markdown，
並按照文件內容一步一步帶我完成。

規則：

1. 一次只帶我做一個步驟。
2. 每一步操作前，先用白話告訴我這一步在做什麼、為什麼要做。
3. 不要假設我知道 Git、GitHub、Repo、Commit、Push、Branch 等術語。
4. 第一次出現術語時請解釋。
5. 每完成一個重要步驟就停下來問我是否理解。
6. 我回答完成或理解後，你才能進下一步。
7. 如果我的畫面跟你的預期不同，先協助我排除問題，不要直接跳下一步。
8. 登入、密碼、Email 驗證、2FA、授權與是否公開等決定，請讓我自己確認。
9. 即使你可以代我執行操作，也要先告訴我你準備做什麼，完成後再說明你剛才做了什麼。
10. 我今天的目標是成功建立 GitHub 帳號、第一個 Repo，並完成第一次 Commit 與 Push。

現在請從第 0 步開始，不要一次把後面的步驟全部告訴我。
```

---

# MVP 成功標準

這個教學 MVP 被視為成功，只需要符合以下條件：

- 一個從未使用 GitHub 的人可以照著完成
- 不需要先自行看 Git 教學
- 使用者知道自己每一步在做什麼
- 成功建立 GitHub 帳號
- 成功建立 Public Repo
- 成功上傳 README.md
- 成功完成 Commit
- 成功完成 Push
- 成功做第二次修改與 Push
- 最後可以把 Repo 網址分享給別人

---

# 目前不需要教的東西

第一輪先不要加入：

- Git Flow
- Rebase
- Merge Conflict
- Pull Request 詳細流程
- GitHub Actions
- Fork
- SSH Key 深入設定
- Branch Strategy
- Conventional Commits
- CI/CD

這些等使用者完成第一個 Repo 之後再學。

---

# 最重要的教學原則

這個流程的成功，不是：

> Codex 幫使用者把 Repo 建好了。

而是：

> **使用者知道 Codex 剛剛帶她做了什麼，而且下一次看到 GitHub 不會再覺得完全陌生。**

Codex 的任務不是展現它會多少 Git。

而是把「第一次使用 GitHub 的門檻」降到最低。
