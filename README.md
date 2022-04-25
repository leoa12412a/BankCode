# BankCode 銀行代號 分行代號

init
```
<script src="//ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>
<script src="/assets2/jquery.bankcode.js" ></script>

<div id="bankcode"></div>

$('#bankcode').bankcode();	
```

set class
```
$('#bankcode').bankcode({
	'css': ['form-control', 'form-control', 'form-control']
});	
```

set default value
```
$('#bankcode').bankcode('set',{
	'bank_name': '聯邦商業銀行',
	'bank_branch_name': '桃園分行',
	'bank_code': '8030032',
});
```
