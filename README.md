# Python を使用して DICOM 画像を処理する

医療情報の複雑化や医療安全の観点からも，医療画像を適切に扱い，理解することは不可欠である．どのように理解するのがベストかを考えた時に実際に手を動かすことであり，実習形式で行うこととしました．

この GitHub 常にプログラムのソースコードを載せているので，各自ローカルもしくは，Google Colaboratory にて動かしてみましょう．
Google Colaboratory には Google アカウントの取得が必要ですが，マシンの性能に左右されないので，便利で簡便です．
基本的にコードは Python で記述しており，Jupyter Notebook にて載せています．


## DICOM ファイルとは
 - DICOM 規格で定められている医用画像などのファイルフォーマットのこと
 - DICOM については他の授業で履修済みとする

## 使用する DICOM ファイル
 - [JIRA](https://www.jira-net.or.jp/dicom/dicom_data_01_02.html) より無料配布の DICOM ファイルを使用
 - [PyDicom](https://github.com/pydicom/pydicom/tree/master/pydicom/data/test_files) より無料配布の DICOM ファイルを使用
 - [ImageJ](https://imagej.nih.gov/ij/images/) より無料配布の DICOM ファイルを使用
 - [OSIRIX](http://www.osirix-viewer.com/resources/dicom-image-library/) より無料配布の DICOM ファイルを使用

## NOTEBOOK

|  番号 | ファイル | 説明 |
| :---: | :--- | :--- |
| 1 | [readDICOM.ipynb](https://github.com/ryskks/usedicom/blob/main/readDICOM.ipynb) | DICOM タグの読み取りと画像表示 |
| 2 | [window.ipynb](https://github.com/ryskks/usedicom/blob/main/window.ipynb) | ウィンドウレベル/幅の調整 |
| 3 | [slice.ipynb](https://github.com/ryskks/usedicom/blob/main/slice.ipynb) |複数のスライス画像を扱う |
| 4 | [multi.ipynb](https://github.com/ryskks/usedicom/blob/main/multi.ipynb) |画像を MPR 表示してみる |
| 5 | [dimension.ipynb](https://github.com/ryskks/usedicom/blob/main/dimension.ipynb) |3 次元表示で観察する |

