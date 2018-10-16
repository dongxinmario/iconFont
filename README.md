# iconFont
批量下载iconFont图标
for(var i = 0,j = document.getElementsByClassName('icon-cover').length;i<j;i+=1){
    document.getElementsByClassName('icon-cover')[i].className += ' myclick'
}

for(var i = 0,j = 531;i<j;i+=1){
    document.getElementsByClassName('myclick')[i].children[0].click()
}
