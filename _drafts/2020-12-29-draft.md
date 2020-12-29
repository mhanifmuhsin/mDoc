---
layout: post
title:  "Aturan Penamaan Identifier Pada Javascript"
date:   2020-12-29 17:09:00 +0700
categories: javascript
---

Aturan Penamaan identifier pada Javascript adalah sebagai berikut :


1. Penamaan variabel, fungsi, kelas, dll, harus diawali dengan huruf atau _underscore_ **_** atau dengan tanda dollar **$**,
untuk selanjutnya boleh angka , huruf, dsb.

	```javascript
	   let username  = "unix";
	   let _username = "unix";
	   let $username = "unix";
	```

2. Semua identifier adalah case sensitif dalam artian membedakan huruf besar dan kecil.

	```javascript 
	   let username = "unix"; 
	   let Username = "unix";
	```

	Kedua variabel diatas kalau dibaca sama, namun ada perbedaan pada huruf pertanama, yaitu besar dan kecil. Hal ini tidak akan menjadi error, karena dianggap berbeda.
	 
3. Semua reserved keyword harus ditulis dalam format lower-case (huruf kecil) contoh : const bukan Const, atau let bukan Let.

	```javascript
       let username = "unix" //benar
       Let username = "unix" //salah
	```

4. Identifier yang berisi lebih dari satu kata sebaiknya ditulis dengan format *camelCase*, kecuali nama kelas atau fungsi yang bertindak sebagai kelas.

	```javascript
	   let idProduct = "001" //benar
	   let IdProduct = "001" //kurang baik

       //function sebagai class
	   function Product (id,name){
	    	this.id = id;
	    	this.name = name;
		}

	   //class
	   class Product {
            constructor(id,name){
            this.id = id;
            this.name = name;
        	}
		}
	```
   
5. Nama identifier tidak boleh menggunakan reserved keywoard.

   ```
    //berikut adalah reserved keywoard Javascript

    await, break, case, catch, class, const, continue, debugger, default, 
    delete,do, else, enum, export,extends, false, finally, for, function, 
    if, implements, import, in, instanceof, interface, let, new, null,
    package, private, protected, public, return, super,switch, this, throw, 
    true, try, typeof, var, void, while, with, yield
   ```