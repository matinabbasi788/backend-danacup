ورود مشتری و دریافت توکن POST /api/customers/login
دریافت لیست محصولات GET /api/products
دریافت جزئیات یک محصول خاص GET /api/products/:id
افزودن محصول به سبد خرید POST /api/cart
دریافت محتویات سبد خرید GET /api/cart
به روزرسانی تعداد یک آیتم در سبد خرید PUT /api/cart/:itemId
حذف یک آیتم از سبد خرید DELETE /api/cart/:itemId
ثبت سفارش جدید POST /api/orders

لیست Endpoin های بخش ادمین

ورود ادمین و دریافت توکن POST /api/admin/login
دریافت لیست محصولات GET /api/admin/products
افزودن محصول جدید POST /api/admin/products
ویرایش اطلاعات محصول PUT /api/admin/products/:id
حذف محصول DELETE /api/admin/products/:id
دریافت لیست دسته بندی ها GET /api/admin/categories
افزودن دسته بندی جدید POST /api/admin/categories
ویرایش دسته بندی PUT /api/admin/categories/:id
حذف دسته بندی DELETE /api/admin/categories/:id
دریافت لیست سفارشات GET /api/admin/orders
تغییر وضعیت سفارش PUT /api/admin/orders/:id