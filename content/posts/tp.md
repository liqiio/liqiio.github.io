---
title: "TP｜MacDown 开发者"
date: "2015-12-23"
categories: 
  - "interview"
tags: 
  - "ω＼"
  - "mac"
  - "developer"
---

### ![tp1](/images/tp1.jpg)

### **介紹一下你自己和所做的工作。**

在網路上用的帳號是 [uranusjr](https://uranusjr.com/)，但因為沒人會念，平常可以叫我 TP，這是我名字的拼音縮寫。現在的工作主要是為農業相關的產業設計自動化系統。聽起來很厲害，但我負責的就是拿到一個規格或一份邏輯，然後用軟體做出來，和一般人也差不多。

我在空閒時間會對一些開源專案提交貢獻，同時自己也維護幾個開源專案，比較有名的應該是 OS X 用的 Markdown 編輯軟體 [MacDown](https://macdown.uranusjr.com/)。

同時也關注一些比較偏社群文化面的議題，目前主要協助 [Django Girls Taipei](https://djangogirls.org/taipei/) 編輯教材，以及不定期舉辦工作坊。這個社群的主要目標是降低科技業對女性的門檻，協助他們踏出對程式設計的第一步，並建構一個較為友善的環境。

### **你都在使用哪些硬件？**

工作上主要使用 2013 年的 13 吋 [MacBook Air](https://www.apple.com/cn/macbook-air/)，另外有台 [Lenovo Yoga](https://www.google.co.uk/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=0ahUKEwis-pvk3fHJAhWGvA8KHWk8DFwQFggeMAA&url=http%3A%2F%2Fshopap.lenovo.com%2Ftw%2Fzh%2Flaptops%2Flenovo%2Fyoga%2F&usg=AFQjCNGcUqPJvVivs2j7_OB02YK_KMVbQQ) 但不太愛用。家裡有一台 2008 年的 20 吋 [iMac](https://www.apple.com/cn/imac/)，但跑起現在的開發軟體太吃力，主要只拿來看影片和上網。狀況允許時會外接 Filco 青軸，主前主力是 [Minila Air 67 鍵](https://www.amazon.com/Majestouch-Tactile-Bluetooth-Keyboard-FFBT67M/dp/B00F3V81VG)與 [Ninja 87 鍵](https://www.amazon.com/Filco-Majestouch-2-Tenkeyless-FKBN87ML-EFB2/dp/B0050ODQEI)。

隨身帶 [iPhone 6](https://www.apple.com/cn/iphone-6/)，之前配 [AKG Q460](https://item.jd.com/407322.html)（不推薦買）但上週壞了，近期先用以前買的 [AKG K318](https://www.amazon.cn/AKG-K318-%E8%80%B3%E5%A1%9E%E5%BC%8F%E7%BA%BF%E6%8E%A7%E9%80%9A%E8%AF%9D%E8%80%B3%E6%9C%BA-%E9%BB%91%E8%89%B2-iPad-iPod-iPhone%E4%BC%B4%E4%BE%A3-%E5%A3%B0%E9%9F%B3%E7%BB%86%E8%85%BB%E5%B9%B3%E8%A1%A1/dp/B007CFQPSC) 擋一下。工作時會用耳擴接 [AKG Q701](https://item.jd.com/391785.html)（這支不錯），但最近覺得無法專心有點想換封閉式。

喜歡用鉛筆，但沒有特別鍾情的款式，最近用的是[這個](https://www.pinkoi.com/product/1IiqaMwd)。

### **軟件呢？**

當然是 [MacDown](https://macdown.uranusjr.com/)。

![tp2](/images/tp2.jpg)

我平常會做的東西種類頗多。工作上主要寫 C++ 和 Python，自己的專案會用到 Objective-C，偶爾還得做一些 sysadmin 的工作，所以用到的環境也會比較雜。一般而言我寫 Cocoa 與 Cocoa Touch 時（例如 MacDown）用 [Xcode](https://www.google.co.uk/url?sa=t&rct=j&q=&esrc=s&source=web&cd=2&cad=rja&uact=8&ved=0ahUKEwiouM-P3_HJAhXDGQ8KHfNoCqcQFggrMAE&url=https%3A%2F%2Fdeveloper.apple.com%2Fxcode%2Fdownload%2F&usg=AFQjCNEeubB_0I7eDGUfczH1T3u2NO7dFA)，如果要寫 Qt 相關的東西（通常是 C++ 與 QML）用 [Qt Creator](https://www.qt.io/ide/)，管理系統用 [Vim](https://www.vim.org/)，其他狀況則會使用 [Sublime Text 3](https://www.sublimetext.com/3)。幸好除了 [Vim](https://www.vim.org/) 之外的環境只要稍微調整（快捷鍵之類的）用起來沒有差太多。

不知為何 Cocoa programming 的工具很多都是基於 Ruby，所以我也稍微懂得寫，平常也會使用例如 [Bundler](https://bundler.io/) 和 [rbenv](https://rbenv.org/) 之類的工具。MacDown 的 Ruby 環境（用在 [CocoaPods](https://cocoapods.org/)）也是用 [Bundler](https://bundler.io/) 來設定。但如果能夠自己選，我還是比較傾向用 Python 來做平常使用的小工具；[MacDown 的 release script](https://github.com/uranusjr/macdown/blob/master/Tools/build_for_release.py) 也是用 Python 做的。

待辦事項是用 [Asana](https://asana.com/) 管理，不過不太喜歡網站介面與 iOS app 很難用（雖然最近大改版後有好一些），偶爾會有點煩惱。之前研究了一下 API 感覺不難，如果有空下一個 project 應該會做這個。如果有空。工作上用 [Slack](https://slack.com/)，但我比較喜歡 [Gitter](https://gitter.im/)。

噢，對了，我偶爾也會寫一些 web application。主要使用的 web framework 是 [Django](https://www.djangoproject.com/)，工作上也有用到 [Flask](https://flask.pocoo.org/)，但除非有特殊原因比較少碰。其他比較常用的 Python 工具：

- [Click](https://click.pocoo.org/5/)
- [Requests](https://docs.python-requests.org/en/latest/)
- [ptpython](https://github.com/jonathanslenders/ptpython/)、[pgcli](https://pgcli.com/) 與 [mycli](https://mycli.net/)
- [PyFlakes](https://pypi.python.org/pypi/pyflakes)、[PEP8](https://www.python.org/dev/peps/pep-0008/) 與 [Flake8](https://pypi.python.org/pypi/flake8)
- [Nose](https://nose.readthedocs.org/en/latest/) 與 [py.test](https://pytest.org/latest/)
- [MoSQL](https://mosql.mosky.tw/)
- [Cuteshop](https://github.com/uranusjr/cuteshop)

最近試了 [xonsh](https://xonsh.org/) 感覺不錯，希望未來可以當成主力 shell（目前用 [Bash](https://www.gnu.org/software/bash/bash.html)）。

### **你最理想的工作環境是什麼？**

合適高度的桌子與合適高度的椅子，不需要管服裝，可以自由調整溫濕度，可以到處走來走去發出聲音不會影響別人，當我不想發出聲音時可以完全安靜。

最好有床和遙控燈可以隨時睡覺（這樣就不是工作環境了啊喂）。

### **你平時獲得工作靈感的方式有哪些？**

如果有事情想不出來我會到處走來走去自言自語，應該很多人覺得我很煩。平常不工作時我會聽音樂，最近迷 [amazarashi](https://www.amazarashi.com/top/) 和 [Goose house](https://goosehouse.jp/)，但聽音樂時就不想其他事情了，也無所謂獲得什麼靈感，只是一種平常放鬆的方法。啊，我有很多東西是在洗澡時想到的，應該也算一種方式？

### **推薦一件生活中的利器給大家。**

當然是 [MacDown](https://macdown.uranusjr.com/)。

其實我在這裡想了好幾個，但最後又覺得好像都不太適合。總覺得每個人的需求都不太一樣，我用的東西也沒什麼特別值得推薦的點。大家就多多嘗試吧，看到別人用什麼就問問別人是怎麼用的，自己模仿看看，試著為自己的需求稍微調整，最後再決定適不適合自己。

最近覺得[碼天狗週刊](https://weekly.codetengu.com/)不錯。不是說多有見地，但是題材很廣，可以多看看別人怎麼做事，我自己雖然很多學不來，至少也能開開眼界。硬體方面，科技的大家應該都不缺來源，生活用品或許可以試試從 [Pinkoi](https://www.pinkoi.com/) 找靈感。

 

加入[利器社群](https://liqi.io/community/)，你也可以分享自己的利器。
