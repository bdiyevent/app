# Create QRIS with JS


1. add this js on the tag header

    QR Kustomfest E Commerce <br>
    https://rawcdn.githack.com/bdiyevent/app/6e92a4f2cba9650daebbccd14f9ffd59875509b0/qrkstmfst-e.js?ecommerce
    <br><br>
    QR Kustomfest Tiket <br>
    https://rawcdn.githack.com/bdiyevent/app/6e92a4f2cba9650daebbccd14f9ffd59875509b0/qrkstmfst-t.js?tiket


2. create an event with a function like below in your element code

   getQR("value", "type");
   
   type => "text" or "image" or "raw"



3. add the following elements to display the QR image

   image :
   \<img id=imageQR>
   <br>
   or
   <br>
   text :
   \<input id=dataQR>>
   <br>
   or
   <br>
   raw : you can create a function to place a qr string return
