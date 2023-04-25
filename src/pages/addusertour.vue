<template>
    
  <section class="bg-white dark:bg-gray-900">
  <div class="py-8 px-10 mx- max-w-1000 lg:py-16">
      <h2 class="mb-4 text-xl font-bold text-gray-900 dark:text-white">ข้อมูลลูกทัวร์ | อุบล</h2>
      <form action="#">
          <div class="grid gap-4 sm:grid-cols-6 sm:gap-6">
              <div class="w-full">
                  <label for="brand" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">ชื่อ</label>
                  <input type="text" name="brand" id="brand" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500" placeholder="" required="">
              </div>
              <div class="w-full">
                  <label for="brand" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">นามสกุล</label>
                  <input type="text" name="brand" id="brand" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500" placeholder="" required="">
              </div>
              <div class="w-full">
                  <label for="brand" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">Surname</label>
                  <input type="text" name="brand" id="brand" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500" placeholder="" required="">
              </div>
              <div class="w-full">
                  <label for="brand" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">Lastname</label>
                  <input type="text" name="brand" id="brand" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500" placeholder="" required="">
              </div>
              <div class="w-full">
                  <label for="brand" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">สัญชาติ</label>
                  <input type="text" name="brand" id="brand" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500" placeholder="" required="">
              </div>
              <div>

<label for="countries" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">เพศ</label>
<select id="countries" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500">
<option selected></option>
<option value="US">ชาย</option>
<option value="CA">หญิง</option>
<option value="FR">อื่นๆ</option>
</select>

</div>
            </div>
            <br>
            <div class="grid gap-4 sm:grid-cols-4 sm:gap-6">
              <div class="w-full">
                  <label for="brand" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">หมายเลขบัตรประชาชน</label>
                  <input type="text" name="brand" id="brand" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500" placeholder="" required="">
              </div>
              <div class="w-full">
                
                <label for="price" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">วัน เดือน ปี เกิด</label>
                <input type="date" id="start" name="trip-start"
value=""
     min="2023-01-01" max="2023-12-31" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500">
            </div>
            <div class="w-full">
                  <label for="brand" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">
เบอร์โทรศัพท์</label>
                  <input type="text" name="brand" id="brand" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500" placeholder="" required="">
              </div>
              <div>

<label for="countries" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">ประเภทเตียง
</label>
<select id="countries" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500">
<option selected></option>
<option value="US">เตียงเดี่ยว</option>
<option value="CA">เตียงคู่</option>

</select>

</div>
              
          </div>
          <br>
          <div class="grid gap-4 sm:grid-cols-3 sm:gap-6">
          <div class="w-full">
                  <label for="price" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">หมายเลขพาสปอร์ต</label>
                  <input type="number" name="price" id="price" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500" placeholder="" required="">
              </div>
              <div class="w-full">
                  <label for="price" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">ตรวจลงตราเลขที่</label>
                  <input type="number" name="price" id="price" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500" placeholder="" required="">
              </div>
              
              <div class="w-full">
                
                  <label for="price" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">
วันที่ออก - วันที่หมด</label>
                  <input type="date" id="start" name="trip-start"
value=""
       min="2023-01-01" max="2023-12-31" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500">
              </div>
           
            </div>
            <br>
            <div class="grid gap-4 sm:grid-cols-3 sm:gap-6">
                <div class="w-full">
                  <label for="brand" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">ที่อยู่ตามบัตรประชาชน</label>
                  <input type="text" name="brand" id="brand" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500" placeholder="" required="">
              </div>
              <div class="w-full">
                  <label for="brand" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">หมายเหตุ</label>
                  <input type="text" name="brand" id="brand" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500" placeholder="" required="">
              </div>
              <div class="grid gap-4 sm:grid-cols-5 sm:gap-5">
          <button type="submit" class= "inline-flex items-center px-5 py-2.5 mt-4 sm:mt-6 text-sm font-medium text-center text-white bg-primary-700 rounded-lg focus:ring-4 focus:ring-primary-200 dark:focus:ring-primary-900 hover:bg-primary-800 bg-blue-500">
            เพิ่มลูกทัวร์
          </button>
        </div>
            </div>
      </form>
   </div>
   <div class="relative overflow-x-auto">
    <table class="w-full text-sm text-left text-gray-500 dark:text-gray-400">
        <thead class="text-xs text-gray-700 uppercase bg-gray-50 dark:bg-gray-700 dark:text-gray-400">
            <tr>
                <th scope="col" class="px-6 py-3">
                    ลำดับ
                </th>
                <th scope="col" class="px-6 py-3">
                    ชื่อ-นามสกุลภาษาไทย
                </th>
                <th scope="col" class="px-6 py-3">
                    หมายเลขบัตรประชาชน
                </th>
                <th scope="col" class="px-6 py-3">
                    ชื่อ-นามสกุลภาษาอังกฤษ
                </th>
                <th scope="col" class="px-6 py-3">
                    หมายเลขพาสปอร์ต
                </th>
                <th scope="col" class="px-6 py-3">
                	วันที่ออก
                </th>
                <th scope="col" class="px-6 py-3">
                    วันที่หมด
                </th>
                <th scope="col" class="px-6 py-3">
                    ว/ด/ป เกิด
                </th>
                <th scope="col" class="px-6 py-3">
                    สัญชาต
                </th>
                <th scope="col" class="px-6 py-3">
                	เพศ
                </th>
                <th scope="col" class="px-6 py-3">
                    ประเภทเตียง
                </th>
                <th scope="col" class="px-6 py-3">
                    ตรวจลงตราเลขที
                </th>
            </tr>
        </thead>
        <tbody>
            <tr class="bg-white border-b dark:bg-gray-800 dark:border-gray-700">
                <th scope="row" class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                  
                </th>
                <td class="px-6 py-4">
                  
                </td>
                <td class="px-6 py-4">
                 
                </td>
                <td class="px-6 py-4">
                   
                </td>
            </tr>
            <tr class="bg-white border-b dark:bg-gray-800 dark:border-gray-700">
                <th scope="row" class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                 
                </th>
                <td class="px-6 py-4">
                  
                </td>
                <td class="px-6 py-4">
                  
                </td>
                <td class="px-6 py-4">
                 
                </td>
            </tr>
            <tr class="bg-white dark:bg-gray-800">
                <th scope="row" class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                  
                </th>
                <td class="px-6 py-4">
                 
                </td>
                <td class="px-6 py-4">
               
                </td>
                <td class="px-6 py-4">
               
                </td>
            </tr>
        </tbody>
    </table>
</div>
</section>

     </template>
     