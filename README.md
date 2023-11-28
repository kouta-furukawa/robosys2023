# name (Windows10 robosys2023)
ロボットシステム学の練習リポジトリ


# plusコマンド
![test](https://github.com/kouta-furukawa/robosys2023/actions/workflows/test.yml/badge.svg)

標準入力から読み込んだ数字を足す。

# Requirement
＊requirements.txt

# Installation
sudo apt update  
sudo apt install python3  
sudo apt-get update  
sudo apt-get install coreutils  
sudo yum install coreutils  
sudo apt install python3-pip   
cd /path/to/your/project  
pip3 install -r requirements.txt  

# Usage
git clone <git@github.com:kouta-furukawa/robosys2023.git>  
cd robosys2023  
chmod +x plus  
./plus  

#for example
seq 5 | ./plus   
(Output) 15  

cd robosys2023/.github/workflows 
git add test.yml  
git commit -m "Add a coment"  
git log -n 1  
git push  

#使用できた環境
Ubuntu 20.40 Windows 


# Author
* Kouta Furukawa  
* 千葉工業大学未来　先進工学部　ロボティクス学科  
* furuko1030@gmail.com  



## 必要なソフトウェア
* Python
  * テスト済み: 3.7〜3.10

## テスト環境
* Ubuntu

© 2023 Kouta Furukawa

#LICENCE
＊このソフトウェアパッケージは,3条項BSDライセンスの下,再配布および使用が許可されています.
＊このパッケージは、BSD由来のコード(©　2023 Kouta Furukawa)を利用しています.
＊このパッケージのコードは,下記のスライド(cc-BY-SA 4.0 by Ryuichi Ueda)のものを,本人の許可を得て自身の著作としたものです.
    * [https://github.com/ryuichiueda/my_slides/blob/master/robosys_2022/lesson3.md](https://github.com/ryuichiueda/my_slides/tree/master/robosys2022)
＊© 2023 Kouta Frukawa 
