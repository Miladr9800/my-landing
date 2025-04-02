<html lang="fa">
<head>
  <meta charset="UTF-8">
  <link rel="icon" href="https://card.thecartek.com/images/ct.png">
  <link rel="stylesheet" href="https://card.thecartek.com/css/app.css">
  <link rel="stylesheet" href="https://card.thecartek.com/css/override.css"><!-- Livewire Styles -->
  <style>
    [wire\:loading], [wire\:loading\.delay], [wire\:loading\.inline-block], [wire\:loading\.inline], [wire\:loading\.block], [wire\:loading\.flex], [wire\:loading\.table], [wire\:loading\.grid], [wire\:loading\.inline-flex] {
        display: none;
    }

    [wire\:loading\.delay\.shortest], [wire\:loading\.delay\.shorter], [wire\:loading\.delay\.short], [wire\:loading\.delay\.long], [wire\:loading\.delay\.longer], [wire\:loading\.delay\.longest] {
        display:none;
    }

    [wire\:offline] {
        display: none;
    }

    [wire\:dirty]:not(textarea):not(input):not(select) {
        display: none;
    }

    input:-webkit-autofill, select:-webkit-autofill, textarea:-webkit-autofill {
        animation-duration: 50000s;
        animation-name: livewireautofill;
    }

    @keyframes livewireautofill { from {} }
</style>
</head>


 <body x-data="{
         openSidebar: false,
         clipboardCopy: false,
         modalQrCode: false,
         clipboard(val) { window.navigator.clipboard.writeText(val);
         this.clipboardCopy = true;
         setTimeout(() => this.clipboardCopy = false, 2000) }
         }">
 
   <div class="container-">
    <div class="panel-content mb-3">
     <div class="container-panel mb-15">
      <div class="container-content" style="max-height: 100vh;">
       <div class="mx-auto border-4 border-gray-200 border-dashed rounded-3xl  pb-5 relative">
        
        
        <div class="md:pl-3 md:pr-3 pr-1 pl-1">
         <div class="flex justify-center">
         <div class="text-center space-y-4">
          <h3 class="text-xl font-bold mt-3">موبایل رضائی</h3>
          <p class="text-sm text-gray-500 mt-0 pt-0" style="margin-top: 0px !important;">فروش اقساطی</p>
         </div>
        </div>
        <div class="flex justify-center space-x-2 gap-2 mt-3 ">
         <button type="submit" class="is-elevated text-white bg-blue-700 justify-center hover:bg-blue-800  transition-all focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-xl text-sm py-2.5 text-center  dark:bg-blue-600 text-nowrap dark:hover:bg-blue-700 dark:focus:ring-blue-800 inline-flex items-center" style="background-color: #3b82f6 !important;" @click="modalQrCode = true"> <span wire:loading.remove="" class="mx-2 transition">QR CODE</span>
          <svg aria-hidden="true" role="status" wire:loading="" class="inline w-4 h-4 me-3 text-white animate-spin transition" viewBox="0 0 100 101" fill="none" xmlns="http://www.w3.org/2000/svg">
           <path d="M100 50.5908C100 78.2051 77.6142 100.591 50 100.591C22.3858 100.591 0 78.2051 0 50.5908C0 22.9766 22.3858 0.59082 50 0.59082C77.6142 0.59082 100 22.9766 100 50.5908ZM9.08144 50.5908C9.08144 73.1895 27.4013 91.5094 50 91.5094C72.5987 91.5094 90.9186 73.1895 90.9186 50.5908C90.9186 27.9921 72.5987 9.67226 50 9.67226C27.4013 9.67226 9.08144 27.9921 9.08144 50.5908Z" fill="#E5E7EB"></path> <path d="M93.9676 39.0409C96.393 38.4038 97.8624 35.9116 97.0079 33.5539C95.2932 28.8227 92.871 24.3692 89.8167 20.348C85.8452 15.1192 80.8826 10.7238 75.2124 7.41289C69.5422 4.10194 63.2754 1.94025 56.7698 1.05124C51.7666 0.367541 46.6976 0.446843 41.7345 1.27873C39.2613 1.69328 37.813 4.19778 38.4501 6.62326C39.0873 9.04874 41.5694 10.4717 44.0505 10.1071C47.8511 9.54855 51.7191 9.52689 55.5402 10.0491C60.8642 10.7766 65.9928 12.5457 70.6331 15.2552C75.2735 17.9648 79.3347 21.5619 82.5849 25.841C84.9175 28.9121 86.7997 32.2913 88.1811 35.8758C89.083 38.2158 91.5421 39.6781 93.9676 39.0409Z" fill="currentColor"></path>
          </svg></button> <button type="submit" class="is-elevated text-white bg-blue-700 justify-center hover:bg-blue-800  transition-all focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-xl text-sm py-2.5 text-center  dark:bg-blue-600 text-nowrap dark:hover:bg-blue-700 dark:focus:ring-blue-800 inline-flex items-center"> <span wire:loading.remove="" class="mx-2 transition">لوکیشن</span>
          <svg aria-hidden="true" role="status" wire:loading="" class="inline w-4 h-4 me-3 text-white animate-spin transition" viewBox="0 0 100 101" fill="none" xmlns="http://www.w3.org/2000/svg">
           <path d="M100 50.5908C100 78.2051 77.6142 100.591 50 100.591C22.3858 100.591 0 78.2051 0 50.5908C0 22.9766 22.3858 0.59082 50 0.59082C77.6142 0.59082 100 22.9766 100 50.5908ZM9.08144 50.5908C9.08144 73.1895 27.4013 91.5094 50 91.5094C72.5987 91.5094 90.9186 73.1895 90.9186 50.5908C90.9186 27.9921 72.5987 9.67226 50 9.67226C27.4013 9.67226 9.08144 27.9921 9.08144 50.5908Z" fill="#E5E7EB"></path> <path d="M93.9676 39.0409C96.393 38.4038 97.8624 35.9116 97.0079 33.5539C95.2932 28.8227 92.871 24.3692 89.8167 20.348C85.8452 15.1192 80.8826 10.7238 75.2124 7.41289C69.5422 4.10194 63.2754 1.94025 56.7698 1.05124C51.7666 0.367541 46.6976 0.446843 41.7345 1.27873C39.2613 1.69328 37.813 4.19778 38.4501 6.62326C39.0873 9.04874 41.5694 10.4717 44.0505 10.1071C47.8511 9.54855 51.7191 9.52689 55.5402 10.0491C60.8642 10.7766 65.9928 12.5457 70.6331 15.2552C75.2735 17.9648 79.3347 21.5619 82.5849 25.841C84.9175 28.9121 86.7997 32.2913 88.1811 35.8758C89.083 38.2158 91.5421 39.6781 93.9676 39.0409Z" fill="currentColor"></path>
          </svg></button> <button type="submit" class="is-elevated text-white bg-blue-700 justify-center hover:bg-blue-800  transition-all focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-xl text-sm py-2.5 text-center  dark:bg-blue-600 text-nowrap dark:hover:bg-blue-700 dark:focus:ring-blue-800 inline-flex items-center"> <span wire:loading.remove="" class="mx-2 transition">دانلود رزومه</span>
          <svg aria-hidden="true" role="status" wire:loading="" class="inline w-4 h-4 me-3 text-white animate-spin transition" viewBox="0 0 100 101" fill="none" xmlns="http://www.w3.org/2000/svg">
           <path d="M100 50.5908C100 78.2051 77.6142 100.591 50 100.591C22.3858 100.591 0 78.2051 0 50.5908C0 22.9766 22.3858 0.59082 50 0.59082C77.6142 0.59082 100 22.9766 100 50.5908ZM9.08144 50.5908C9.08144 73.1895 27.4013 91.5094 50 91.5094C72.5987 91.5094 90.9186 73.1895 90.9186 50.5908C90.9186 27.9921 72.5987 9.67226 50 9.67226C27.4013 9.67226 9.08144 27.9921 9.08144 50.5908Z" fill="#E5E7EB"></path> <path d="M93.9676 39.0409C96.393 38.4038 97.8624 35.9116 97.0079 33.5539C95.2932 28.8227 92.871 24.3692 89.8167 20.348C85.8452 15.1192 80.8826 10.7238 75.2124 7.41289C69.5422 4.10194 63.2754 1.94025 56.7698 1.05124C51.7666 0.367541 46.6976 0.446843 41.7345 1.27873C39.2613 1.69328 37.813 4.19778 38.4501 6.62326C39.0873 9.04874 41.5694 10.4717 44.0505 10.1071C47.8511 9.54855 51.7191 9.52689 55.5402 10.0491C60.8642 10.7766 65.9928 12.5457 70.6331 15.2552C75.2735 17.9648 79.3347 21.5619 82.5849 25.841C84.9175 28.9121 86.7997 32.2913 88.1811 35.8758C89.083 38.2158 91.5421 39.6781 93.9676 39.0409Z" fill="currentColor"></path>
          </svg></button>
         <form action="https://card.thecartek.com/download-vcf/25" method="post">
          <input type="hidden" name="_token" value="5bjKvZp2jaVIhv6xf9O9BEY7HCv0EvEC5XvUl7QX"> <button type="submit" class="is-elevated text-white bg-blue-700 justify-center hover:bg-blue-800  transition-all focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-xl text-sm py-2.5 text-center  dark:bg-blue-600 text-nowrap dark:hover:bg-blue-700 dark:focus:ring-blue-800 inline-flex items-center" style="background-color: #3b82f6 !important;"> <span wire:loading.remove="" class="mx-2 transition">ذخیره مخاطب</span>
           <svg aria-hidden="true" role="status" wire:loading="" class="inline w-4 h-4 me-3 text-white animate-spin transition" viewBox="0 0 100 101" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M100 50.5908C100 78.2051 77.6142 100.591 50 100.591C22.3858 100.591 0 78.2051 0 50.5908C0 22.9766 22.3858 0.59082 50 0.59082C77.6142 0.59082 100 22.9766 100 50.5908ZM9.08144 50.5908C9.08144 73.1895 27.4013 91.5094 50 91.5094C72.5987 91.5094 90.9186 73.1895 90.9186 50.5908C90.9186 27.9921 72.5987 9.67226 50 9.67226C27.4013 9.67226 9.08144 27.9921 9.08144 50.5908Z" fill="#E5E7EB"></path> <path d="M93.9676 39.0409C96.393 38.4038 97.8624 35.9116 97.0079 33.5539C95.2932 28.8227 92.871 24.3692 89.8167 20.348C85.8452 15.1192 80.8826 10.7238 75.2124 7.41289C69.5422 4.10194 63.2754 1.94025 56.7698 1.05124C51.7666 0.367541 46.6976 0.446843 41.7345 1.27873C39.2613 1.69328 37.813 4.19778 38.4501 6.62326C39.0873 9.04874 41.5694 10.4717 44.0505 10.1071C47.8511 9.54855 51.7191 9.52689 55.5402 10.0491C60.8642 10.7766 65.9928 12.5457 70.6331 15.2552C75.2735 17.9648 79.3347 21.5619 82.5849 25.841C84.9175 28.9121 86.7997 32.2913 88.1811 35.8758C89.083 38.2158 91.5421 39.6781 93.9676 39.0409Z" fill="currentColor"></path>
           </svg></button>
       
        </div>
        <div class="px-5 pt-3">
         <div class="grid grid-cols-1 gap-2">
          <a href="tel:09189444481" class="relative overflow-hidden  pr-2 transition-all text-gray-700 bg-gray-200 hover:bg-blue-600 hover:text-white w-full h-8 rounded-xl p-6">
           <div class="flex absolute inset-y-0 left-0 items-center pointer-events-none pl-2">
            <label class="text-sm ml-2" style="font-family:Tahoma;">09189444481</label> <span class="pl-2 text-gray-300">|</span>
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6 ml-2" style="color:#f59e0b">
             <path stroke-linecap="round" stroke-linejoin="round" d="M10.5 1.5H8.25A2.25 2.25 0 006 3.75v16.5a2.25 2.25 0 002.25 2.25h7.5A2.25 2.25 0 0018 20.25V3.75a2.25 2.25 0 00-2.25-2.25H13.5m-3 0V3h3V1.5m-3 0h3m-3 18.75h3"></path>
            </svg>
           </div></a> <a href="https://t.me/mobilerezaei_ir" class="relative overflow-hidden  pr-2 transition-all  text-gray-700 bg-gray-200 hover:bg-blue-600 hover:text-white w-full h-8 rounded-xl p-6">
           <div class="flex absolute inset-y-0 left-0 items-center pointer-events-none pl-2">
            <label class="text-sm ml-2" style="font-family:Tahoma; direction:ltr; ">mobilerezaei_ir</label> <span class="pl-2 text-gray-300">|</span>
            <svg class="w-5 h-5 ml-2 fill-current" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 496 512" style="color:#2563eb">
             <path d="M248,8C111.033,8,0,119.033,0,256S111.033,504,248,504,496,392.967,496,256,384.967,8,248,8ZM362.952,176.66c-3.732,39.215-19.881,134.378-28.1,178.3-3.476,18.584-10.322,24.816-16.948,25.425-14.4,1.326-25.338-9.517-39.287-18.661-21.827-14.308-34.158-23.215-55.346-37.177-24.485-16.135-8.612-25,5.342-39.5,3.652-3.793,67.107-61.51,68.335-66.746.153-.655.3-3.1-1.154-4.384s-3.59-.849-5.135-.5q-3.283.746-104.608,69.142-14.845,10.194-26.894,9.934c-8.855-.191-25.888-5.006-38.551-9.123-15.531-5.048-27.875-7.717-26.8-16.291q.84-6.7,18.45-13.7,108.446-47.248,144.628-62.3c68.872-28.647,83.183-33.623,92.511-33.789,2.052-.034,6.639.474,9.61,2.885a10.452,10.452,0,0,1,3.53,6.716A43.765,43.765,0,0,1,362.952,176.66Z"></path>
            </svg>
           </div></a> <a href="https://api.whatsapp.com/send?phone=989189444481" class="relative overflow-hidden  pr-2 transition-all  text-gray-700 bg-gray-200 hover:bg-blue-600 hover:text-white w-full h-8 rounded-xl p-6">
           <div class="flex absolute inset-y-0 left-0 items-center pointer-events-none pl-2">
            <label class="text-sm ml-2" style="font-family:Tahoma; direction:ltr; ">09189444481</label> <span class="pl-2 text-gray-300">|</span>
            <svg class="w-6 h-6 ml-2 fill-current" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512" style="color:#10b981">
             <path d="M380.9 97.1C339 55.1 283.2 32 223.9 32c-122.4 0-222 99.6-222 222 0 39.1 10.2 77.3 29.6 111L0 480l117.7-30.9c32.4 17.7 68.9 27 106.1 27h.1c122.3 0 224.1-99.6 224.1-222 0-59.3-25.2-115-67.1-157zm-157 341.6c-33.2 0-65.7-8.9-94-25.7l-6.7-4-69.8 18.3L72 359.2l-4.4-7c-18.5-29.4-28.2-63.3-28.2-98.2 0-101.7 82.8-184.5 184.6-184.5 49.3 0 95.6 19.2 130.4 54.1 34.8 34.9 56.2 81.2 56.1 130.5 0 101.8-84.9 184.6-186.6 184.6zm101.2-138.2c-5.5-2.8-32.8-16.2-37.9-18-5.1-1.9-8.8-2.8-12.5 2.8-3.7 5.6-14.3 18-17.6 21.8-3.2 3.7-6.5 4.2-12 1.4-32.6-16.3-54-29.1-75.5-66-5.7-9.8 5.7-9.1 16.3-30.3 1.8-3.7.9-6.9-.5-9.7-1.4-2.8-12.5-30.1-17.1-41.2-4.5-10.8-9.1-9.3-12.5-9.5-3.2-.2-6.9-.2-10.6-.2-3.7 0-9.7 1.4-14.8 6.9-5.1 5.6-19.4 19-19.4 46.3 0 27.3 19.9 53.7 22.6 57.4 2.8 3.7 39.1 59.7 94.8 83.8 35.2 15.2 49 16.5 66.6 13.9 10.7-1.6 32.8-13.4 37.4-26.4 4.6-13 4.6-24.1 3.2-26.4-1.3-2.5-5-3.9-10.5-6.6z"></path>
            </svg>
           </div></a> <a href="https://www.instagram.com/mobilerezaei.ir" class="relative overflow-hidden  pr-2 transition-all  text-gray-700 bg-gray-200 hover:bg-blue-600 hover:text-white w-full h-8 rounded-xl p-6">
           <div class="flex absolute inset-y-0 left-0 items-center pointer-events-none pl-2">
            <label class="text-sm ml-2" style="font-family:Tahoma; direction:ltr; ">mobilerezaei.ir</label> <span class="pl-2 text-gray-300">|</span>
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512" class="w-6 h-6 ml-2 " style="color:#ef4444">
             <path fill="currentColor" d="M224.1 141c-63.6 0-114.9 51.3-114.9 114.9s51.3 114.9 114.9 114.9S339 319.5 339 255.9 287.7 141 224.1 141zm0 189.6c-41.1 0-74.7-33.5-74.7-74.7s33.5-74.7 74.7-74.7 74.7 33.5 74.7 74.7-33.6 74.7-74.7 74.7zm146.4-194.3c0 14.9-12 26.8-26.8 26.8-14.9 0-26.8-12-26.8-26.8s12-26.8 26.8-26.8 26.8 12 26.8 26.8zm76.1 27.2c-1.7-35.9-9.9-67.7-36.2-93.9-26.2-26.2-58-34.4-93.9-36.2-37-2.1-147.9-2.1-184.9 0-35.8 1.7-67.6 9.9-93.9 36.1s-34.4 58-36.2 93.9c-2.1 37-2.1 147.9 0 184.9 1.7 35.9 9.9 67.7 36.2 93.9s58 34.4 93.9 36.2c37 2.1 147.9 2.1 184.9 0 35.9-1.7 67.7-9.9 93.9-36.2 26.2-26.2 34.4-58 36.2-93.9 2.1-37 2.1-147.8 0-184.8zM398.8 388c-7.8 19.6-22.9 34.7-42.6 42.6-29.5 11.7-99.5 9-132.1 9s-102.7 2.6-132.1-9c-19.6-7.8-34.7-22.9-42.6-42.6-11.7-29.5-9-99.5-9-132.1s-2.6-102.7 9-132.1c7.8-19.6 22.9-34.7 42.6-42.6 29.5-11.7 99.5-9 132.1-9s102.7-2.6 132.1 9c19.6 7.8 34.7 22.9 42.6 42.6 11.7 29.5 9 99.5 9 132.1s2.7 102.7-9 132.1z"></path>
            </svg>
           </div></a></a>
          <div class="relative  text-gray-700 bg-gray-200 overflow-hidden  pr-2 hover:bg-blue-600 transition-all hover:text-white w-full h-8 rounded-xl p-6 flex flex-wrap overflow-x-auto">
           <a href="#" class="flex absolute inset-y-0 left-0 items-center pointer-events-none pl-2 "> <label class="text-sm ml-2 text-left" style="font-family:Tahoma;"> <span>6037997452271092</span> </label> <span class="pl-2 text-gray-300">|</span>
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6 ml-2" style="color:#f43f5e">
             <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 8.25h19.5M2.25 9h19.5m-16.5 5.25h6m-6 2.25h3m-3.75 3h15a2.25 2.25 0 002.25-2.25V6.75A2.25 2.25 0 0019.5 4.5h-15a2.25 2.25 0 00-2.25 2.25v10.5A2.25 2.25 0 004.5 19.5z"></path>
            </svg></a> <button type="button" class=" absolute right-0 inset-y-0 items-center cursor-pointer" @click="clipboard('6037997452271092')">
            <div class="bg-gray-100 hover:bg-gray-200 text-gray-700 rounded-xl px-2 py-2 mr-1">
             <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
              <path stroke-linecap="round" stroke-linejoin="round" d="M9 12h3.75M9 15h3.75M9 18h3.75m3 .75H18a2.25 2.25 0 002.25-2.25V6.108c0-1.135-.845-2.098-1.976-2.192a48.424 48.424 0 00-1.123-.08m-5.801 0c-.065.21-.1.433-.1.664 0 .414.336.75.75.75h4.5a.75.75 0 00.75-.75 2.25 2.25 0 00-.1-.664m-5.8 0A2.251 2.251 0 0113.5 2.25H15c1.012 0 1.867.668 2.15 1.586m-5.8 0c-.376.023-.75.05-1.124.08C9.095 4.01 8.25 4.973 8.25 6.108V8.25m0 0H4.875c-.621 0-1.125.504-1.125 1.125v11.25c0 .621.504 1.125 1.125 1.125h9.75c.621 0 1.125-.504 1.125-1.125V9.375c0-.621-.504-1.125-1.125-1.125H8.25zM6.75 12h.008v.008H6.75V12zm0 3h.008v.008H6.75V15zm0 3h.008v.008H6.75V18z"></path>
             </svg>
            </div></button>
          </div>
          <div class="relative  text-gray-700 bg-gray-200 overflow-hidden  pr-2 hover:bg-blue-600 transition-all hover:text-white w-full h-8 rounded-xl p-6 flex flex-wrap overflow-x-auto">
           <a href="#" class="flex absolute inset-y-0 left-0 items-center pointer-events-none pl-2 "> <label class="text-sm ml-2 text-left" style="font-family:Tahoma;"> <span>IR800170000000109773132007</span> </label> <span class="pl-2 text-gray-300">|</span>
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6 ml-2" style="color:#f97316">
             <path stroke-linecap="round" stroke-linejoin="round" d="M9 12h3.75M9 15h3.75M9 18h3.75m3 .75H18a2.25 2.25 0 002.25-2.25V6.108c0-1.135-.845-2.098-1.976-2.192a48.424 48.424 0 00-1.123-.08m-5.801 0c-.065.21-.1.433-.1.664 0 .414.336.75.75.75h4.5a.75.75 0 00.75-.75 2.25 2.25 0 00-.1-.664m-5.8 0A2.251 2.251 0 0113.5 2.25H15c1.012 0 1.867.668 2.15 1.586m-5.8 0c-.376.023-.75.05-1.124.08C9.095 4.01 8.25 4.973 8.25 6.108V8.25m0 0H4.875c-.621 0-1.125.504-1.125 1.125v11.25c0 .621.504 1.125 1.125 1.125h9.75c.621 0 1.125-.504 1.125-1.125V9.375c0-.621-.504-1.125-1.125-1.125H8.25zM6.75 12h.008v.008H6.75V12zm0 3h.008v.008H6.75V15zm0 3h.008v.008H6.75V18z"></path>
            </svg></a> <button type="button" class=" absolute right-0 inset-y-0 items-center cursor-pointer" @click="clipboard('IR800170000000109773132007')">
            <div class="bg-gray-100 hover:bg-gray-200 text-gray-700 rounded-xl px-2 py-2 mr-1">
             <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
              <path stroke-linecap="round" stroke-linejoin="round" d="M9 12h3.75M9 15h3.75M9 18h3.75m3 .75H18a2.25 2.25 0 002.25-2.25V6.108c0-1.135-.845-2.098-1.976-2.192a48.424 48.424 0 00-1.123-.08m-5.801 0c-.065.21-.1.433-.1.664 0 .414.336.75.75.75h4.5a.75.75 0 00.75-.75 2.25 2.25 0 00-.1-.664m-5.8 0A2.251 2.251 0 0113.5 2.25H15c1.012 0 1.867.668 2.15 1.586m-5.8 0c-.376.023-.75.05-1.124.08C9.095 4.01 8.25 4.973 8.25 6.108V8.25m0 0H4.875c-.621 0-1.125.504-1.125 1.125v11.25c0 .621.504 1.125 1.125 1.125h9.75c.621 0 1.125-.504 1.125-1.125V9.375c0-.621-.504-1.125-1.125-1.125H8.25zM6.75 12h.008v.008H6.75V12zm0 3h.008v.008H6.75V15zm0 3h.008v.008H6.75V18z"></path>
             </svg>
            </div></button>
          </div>
          <div @click="clipboard('ایلام سرابله خیابان ولیعصر نبش پاساژ محمدی')" class="relative text-gray-700 bg-gray-200 hover:bg-blue-600 transition-all hover:text-white w-full min-h-8 rounded-xl p-6 text-center flex items-center justify-center">
           <h6 style="font-family: Tahoma;
                                        font-size: 15px;
                                        line-height: 1.31rem;" class="text-sm ml-2">ایلام سرابله خیابان ولیعصر نبش پاساژ محمدی</h6>
          </div><a href="mailto:mmmmmm@gmail.com" class="relative overflow-hidden  pr-2 transition-all text-gray-700 bg-gray-200 hover:bg-blue-600 hover:text-white w-full h-8 rounded-xl p-6">
           <div class="flex absolute inset-y-0 left-0 items-center pointer-events-none pl-2">
            <label style="font-family:Tahoma;" class="text-sm ml-2">mobilerezaei.ir@gmail.com</label> <span class="pl-2 text-gray-300">|</span>
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6 ml-2" style="color:#14b8a6">
             <path stroke-linecap="round" stroke-linejoin="round" d="M21.75 6.75v10.5a2.25 2.25 0 01-2.25 2.25h-15a2.25 2.25 0 01-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0019.5 4.5h-15a2.25 2.25 0 00-2.25 2.25m19.5 0v.243a2.25 2.25 0 01-1.07 1.916l-7.5 4.615a2.25 2.25 0 01-2.36 0L3.32 8.91a2.25 2.25 0 01-1.07-1.916V6.75"></path>
            </svg>
           </div></a>
         
   
</body></html>
