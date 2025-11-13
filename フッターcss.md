footer{
position: absolute; サイト上での位置を動かせるようにする
bottom: 30px;　下から30pxの位置に置く
width: 100vw;  横幅を画面幅からみて100%の大きさにする
}
.footer-logo{
    display: flex;　横並びにする　ブロック要素にする
    justify-content: center;　横方向で中央ぞろえ
}
.footer-link{
    color: gray;　文字の色をグレーに
    text-decoration: none;　テキストのデザインをリセットする
    display: flex;　　ブロック要素にする
    justify-content: center;　真ん中におく
    margin-top: 12px;　上方向に余白を12pxおく
}
.footer-icon-list{
    list-style: none;　もともとのリストスタイルをリセットする
    display: flex;　　横並びにする
    justify-content: center;　真ん中におく
}
.footer-icon-item{
    list-style: none;　リストのスタイルをリセットする
    width:65%;　横幅をサイトの65%の大きさで設定する
}
small{
    display: flex;　
    justify-content:center ;
    color: gray;
}
.copy{
    border-top: solid;
    border-color: #eeeeee;
    padding:20px;

}