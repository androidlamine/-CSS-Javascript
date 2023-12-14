<!DOCTYPE html>
<html>
<head>
<title>Zamanlı Popup Afiş Reklam Alanı</title>
<style>
/*<![CDATA[*/
.is-hide{
    display:none;
    visibility:hidden;
}
 .popup-box{
    position:fixed;
    top:0;
    left:0;
    right:0;
    bottom:0;
    width:100%;
    z-index:3
}
 .popup-box-content{
    width:800px;
    height:450px;
    display:block;
    position:absolute;
    top:50%;
    left:50%;
    border-radius:3px;
    margin:-225px 0 0 -420px;
    box-shadow:0 3px 20px 0 rgba(0,0,0,.5);
    z-index:2
}
 .popup-content{
    background:#fff;
    display:block;
    width:100%;
    height:100%;
    border-radius:3px;
    overflow:hidden
}
 .popup-overlay{
    background:#ff5722;
    position:absolute;
    top:0;
    left:0;
    bottom:0;
    width:100%;
    z-index:1
}
 .popup-box-close-button {
     background: #fff;
     position: absolute;
     width:2em;
     height:2em;
     line-height:2em;
     text-align: center;
     top:-1em;
     right: -1em;
     box-shadow: 0 -1px 1px 0 rgba(0,0,0,.2);
     border: none;
     border-radius: 50%;
     cursor:pointer;
     padding:0;
     outline:none
}
 .popup-box-close-button svg{
    vertical-align:middle
}
 .popup-content img{
    display:block;
    width:100%;
    height:100%;
    border-radius:3px;
}
 .popup-flow-box{
    position:relative;
    overflow:hidden
}
 @media screen and (max-width:800px){
    .popup-box-content{
        width:90%;
        height:auto;
        top:20%;
        border-radius:3px;
        margin:0 0 0 -45%
    }
     .popup-content img{
        border-radius:3px;
        height:auto
    }
}
/*]]>*/
</style>
</head>
<body>
<div class='popup-box is-hide' id='popup-box'>
<div aria-label='Close' class="popup-overlay" onclick='document.getElementById("popup-box").style.display="none";removeClassonBody();' role="button" tabindex="0"></div>
<div class='popup-box-content'>
        <a href='https://androidlamine.blogspot.com' rel='noopener noreferrer' target='_blank' title='CSS ve Javascript Kodu ile Zamanlı Popup Afiş Reklam Alanı Oluşturma'>
            <div class='popup-content'>
                <img alt='CSS ve Javascript Kodu ile Zamanlı Popup Afiş Reklam Alanı Oluşturma' height='318' src='https://3.bp.blogspot.com/-_C3Ymu7B5uI/XNC5mIlfYXI/AAAAAAAAKV0/DF87gIEF_Kg42QUIdPP4Mu1sf8vcTRCTgCLcBGAs/s1600/ramazan.webp' title='CSS ve Javascript Kodu ile Zamanlı Popup Afiş Reklam Alanı Oluşturma' width='635'
                />
            </div>
        </a>
<button aria-label='Close' class='popup-box-close-button' onclick='document.getElementById("popup-box").style.display="none";removeClassonBody();'><svg height='24' viewBox='0 0 24 24' width='24'><path d='M19,6.41L17.59,5L12,10.59L6.41,5L5,6.41L10.59,12L5,17.59L6.41,19L12,13.41L17.59,19L19,17.59L13.41,12L19,6.41Z' fill='#333'></path></svg></button>
</div>
</div>
<script>
//<![CDATA[
setTimeout(function(){
 document.getElementById('popup-box').classList.remove('is-hide');
 document.body.className+=" popup-flow-box"
 }, 4800);
function removeClassonBody(){var element=document.body;element.className=element.className.replace(/\bpopup-flow-box\b/g,"")}
//]]>
</script>
</body>
</html>
