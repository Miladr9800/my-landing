<!DOCTYPE html>
<html lang="fa">
<head>
    <meta charset="UTF-8">
    <link rel="icon" href="https://card.thecartek.com/images/ct.png">
    <link rel="stylesheet" href="https://card.thecartek.com/css/app.css">
    <link rel="stylesheet" href="https://card.thecartek.com/css/override.css">
    <!-- لینک به FontAwesome برای استفاده از آیکون‌ها -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        [wire\:loading], [wire\:loading\.delay], [wire\:offline], [wire\:dirty]:not(textarea):not(input):not(select) {
            display: none;
        }
        input:-webkit-autofill, select:-webkit-autofill, textarea:-webkit-autofill {
            animation-duration: 50000s;
            animation-name: livewireautofill;
        }
        @keyframes livewireautofill { from {} }
    </style>
</head>
<body x-data="{ openSidebar: false, clipboardCopy: false, modalQrCode: false, clipboard(val) { navigator.clipboard.writeText(val); this.clipboardCopy = true; setTimeout(() => this.clipboardCopy = false, 2000) }}">
    <div class="container-">
        <div class="panel-content mb-3">
            <div class="container-panel mb-15">
                <div class="container-content" style="max-height: 100vh;">
                    <div class="mx-auto border-4 border-gray-200 border-dashed rounded-3xl pb-5 relative">
                        <div class="md:px-3 px-1">
                            <div class="flex justify-center">
                                <div class="text-center space-y-4">
                                    <h3 class="text-xl font-bold mt-3">موبایل رضائی</h3>
                                    <p class="text-sm text-gray-500 mt-0">فروش اقساطی</p>
                                </div>
                            </div>
                            <div class="flex justify-center gap-2 mt-3">
                                <button class="is-elevated text-white bg-blue-700 hover:bg-blue-800 transition-all focus:ring-4 focus:outline-none font-medium rounded-xl text-sm py-2.5 text-center inline-flex items-center" @click="modalQrCode = true" aria-label="نمایش QR Code">
                                    <span class="mx-2">QR CODE</span>
                                </button>
                                <button class="is-elevated text-white bg-blue-700 hover:bg-blue-800 transition-all focus:ring-4 focus:outline-none font-medium rounded-xl text-sm py-2.5 text-center inline-flex items-center" aria-label="نمایش لوکیشن">
                                    لوکیشن
                                </button>
                                <button class="is-elevated text-white bg-blue-700 hover:bg-blue-800 transition-all focus:ring-4 focus:outline-none font-medium rounded-xl text-sm py-2.5 text-center inline-flex items-center" aria-label="دانلود رزومه">
                                    دانلود رزومه
                                </button>
                                <form action="https://card.thecartek.com/download-vcf/25" method="post">
                                    <input type="hidden" name="_token" value="5bjKvZp2jaVIhv6xf9O9BEY7HCv0EvEC5XvUl7QX">
                                    <button class="is-elevated text-white bg-blue-700 hover:bg-blue-800 transition-all focus:ring-4 focus:outline-none font-medium rounded-xl text-sm py-2.5 text-center inline-flex items-center" aria-label="ذخیره مخاطب">
                                        ذخیره مخاطب
                                    </button>
                                </form>
                            </div>
                            <div class="px-5 pt-3">
                                <div class="grid grid-cols-1 gap-2">
                                    <!-- لینک تماس با شماره تلفن -->
                                    <a href="tel:09189444481" class="relative overflow-hidden pr-2 transition-all text-gray-700 bg-gray-200 hover:bg-blue-600 hover:text-white w-full h-8 rounded-xl p-6" aria-label="تماس با 09189444481">
                                        <div class="flex absolute inset-y-0 left-0 items-center pl-2">
                                            <i class="fas fa-phone-alt text-lg text-gray-400 mr-2"></i>
                                            <label class="text-sm ml-2">09189444481</label>
                                            <span class="pl-2 text-gray-300">|</span>
                                        </div>
                                    </a>
                                    <!-- لینک تلگرام -->
                                    <a href="https://t.me/username" class="relative overflow-hidden pr-2 transition-all text-gray-700 bg-gray-200 hover:bg-blue-600 hover:text-white w-full h-8 rounded-xl p-6" aria-label="لینک به تلگرام">
                                        <div class="flex absolute inset-y-0 left-0 items-center pl-2">
                                            <i class="fab fa-telegram-plane text-lg text-gray-400 mr-2"></i>
                                            <label class="text-sm ml-2">تلگرام</label>
                                        </div>
                                    </a>
                                    <!-- لینک واتس اپ -->
                                    <a href="https://wa.me/09189444481" class="relative overflow-hidden pr-2 transition-all text-gray-700 bg-gray-200 hover:bg-blue-600 hover:text-white w-full h-8 rounded-xl p-6" aria-label="لینک به واتس اپ">
                                        <div class="flex absolute inset-y-0 left-0 items-center pl-2">
                                            <i class="fab fa-whatsapp text-lg text-gray-400 mr-2"></i>
                                            <label class="text-sm ml-2">واتس‌اپ</label>
                                        </div>
                                    </a>
                                    <!-- لینک اینستاگرام -->
                                    <a href="https://instagram.com/username" class="relative overflow-hidden pr-2 transition-all text-gray-700 bg-gray-200 hover:bg-blue-600 hover:text-white w-full h-8 rounded-xl p-6" aria-label="لینک به اینستاگرام">
                                        <div class="flex absolute inset-y-0 left-0 items-center pl-2">
                                            <i class="fab fa-instagram text-lg text-gray-400 mr-2"></i>
                                            <label class="text-sm ml-2">اینستاگرام</label>
                                        </div>
                                    </a>
                                    <!-- ایمیل -->
                                    <a href="mailto:example@example.com" class="relative overflow-hidden pr-2 transition-all text-gray-700 bg-gray-200 hover:bg-blue-600 hover:text-white w-full h-8 rounded-xl p-6" aria-label="ارسال ایمیل">
                                        <div class="flex absolute inset-y-0 left-0 items-center pl-2">
                                            <i class="fas fa-envelope text-lg text-gray-400 mr-2"></i>
                                            <label class="text-sm ml-2">ایمیل</label>
                                        </div>
                                    </a>
                                    <!-- آدرس -->
                                    <a href="https://www.google.com/maps?q=your+address" class="relative overflow-hidden pr-2 transition-all text-gray-700 bg-gray-200 hover:bg-blue-600 hover:text-white w-full h-8 rounded-xl p-6" aria-label="مشاهده آدرس">
                                        <div class="flex absolute inset-y-0 left-0 items-center pl-2">
                                            <i class="fas fa-map-marker-alt text-lg text-gray-400 mr-2"></i>
                                            <label class="text-sm ml-2">آدرس</label>
                                        </div>
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
