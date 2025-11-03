# 本章回顧

## 核心結論

本章的結論是，伺服器算繪和 hydration 是強大的技術，可以明顯改善 web 應用程式的效能、使用者體驗，和 SEO。React 提供豐富的伺服器算繪 API，例如：
- `renderToPipeableStream`
- `renderToString`
- `renderToReadableStream`

每一個 API 都有其優勢和取捨。瞭解這些 API 並根據應用程式的大小、伺服器環境和開發經驗等因素來選擇適當的 API，可以優化 React 應用程式的伺服器端和用戶端效能。


---
hideInToc: true
---

## API 比較分析

**renderToString**
- 適用於小型應用程式且簡單直覺的伺服器算繪 API
- 由於它具有同步性質，且可能阻塞事件迴圈，對於大型應用程式來說可能不是最有效率的選擇

**renderToPipeableStream**  
- 一款更高階、更靈活的 API
- 可讓你更仔細地控制算繪過程
- 並改善與其他 Node.js 串流的整合
- 因而比較適合大型應用程式

---

# 複習問題

1. 在 React 應用程式中使用伺服器渲染的主要優勢是什麼？

2. hydration 在 React 中是如何工作的？為什麼它很重要？

3. 什麼是 resumability？它聲稱比 hydration 好在哪裡？

4. client-only 渲染的主要優勢和缺點是什麼？

5. React 的 `renderToReadableStream` 和 `renderToPipeableStream` API 的主要區別是什麼？

---

# 下回預告

## 探索更高階的 React 開發

掌握伺服器算繪和 hydration 之後，你可以開始探索更高階的 React 開發主題了。在下一章，我們將深入研究並行 React。隨著 web 應用程式變得越來越複雜，處理非同步操作對於建立流暢的使用者體驗而言也越來越重要。

## 並行 React 的重要性

學會利用並行 React 有助於創造高效能、可擴展，且方便使用者的應用程式，輕鬆地處理複雜的資料互動。因此，保持專注，做好提升 React 技能的準備，我們將繼續深入探索並行 React 的領域！


