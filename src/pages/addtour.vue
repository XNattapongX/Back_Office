<template>
    
 <div class="grid gap-1 sm:grid-cols-2 sm:gap-0.2">
  <section class="bg-white dark:bg-gray-900">
  <div class="py-8 px-1 mx-auto max-w-2xl lg:py-16">
      <h2 class="mb-4 text-xl font-bold text-gray-900 dark:text-white">ข้อมูลทัวร์</h2>
      <form action="#">
          <div class="grid gap-4 sm:grid-cols-2 sm:gap-6">
              <div class="w-full">
                  <label for="brand" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">ชื่อทริปทัวร์</label>
                  <input type="text" name="brand" id="brand" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500" placeholder="" required="">
              </div>
              <div class="w-full">
                  <label for="brand" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">ชื่อโปรแกรมทัวร์</label>
                  <input type="text" name="brand" id="brand" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500" placeholder="" required="">
              </div>
            </div>
            <br>
            <div class="grid gap-4 sm:grid-cols-3 sm:gap-6">
              <div class="w-full">
                  <label for="brand" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">ชื่อไกด์</label>
                  <input type="text" name="brand" id="brand" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500" placeholder="" required="">
              </div>
              <div class="w-full">
                  <label for="price" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">เบอร์โทร</label>
                  <input type="number" name="price" id="price" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500" placeholder="" required="">
              </div>
              <div>
                <button type="submit" class="inline-flex items-center px-5 py-2.5 mt-4 sm:mt-6 text-sm font-medium text-center text-white bg-primary-700 rounded-lg focus:ring-4 focus:ring-primary-200 dark:focus:ring-primary-900 hover:bg-primary-800">
              เพิ่มไกด์
          </button>
        </div>
              <div class="sm:col-span-5">
                  <label for="description" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">ชื่อไกด์</label>
                  <textarea id="description" rows="8" class="block p-2.5 w-full text-sm text-gray-900 bg-gray-50 rounded-lg border border-gray-300 focus:ring-primary-500 focus:border-primary-500 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500" placeholder="ไม่มีข้อมูล"></textarea>
              </div>
          </div>
          <br>
          <div class="grid gap-4 sm:grid-cols-3 sm:gap-6">
          <div class="w-full">
                  <label for="price" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">จำนวนวัน</label>
                  <input type="number" name="price" id="price" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500" placeholder="" required="">
              </div>
              <div class="w-full">
                  <label for="price" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">จำนวนคืน</label>
                  <input type="number" name="price" id="price" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500" placeholder="" required="">
              </div>
              
              <div class="w-full">
                
                  <label for="price" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">ระยะเวลา</label>
                  <input type="date" id="start" name="trip-start"
value=""
       min="2023-01-01" max="2023-12-31" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500">
              </div>
           
            </div>
            <br>
            <div class="grid gap-4 sm:grid-cols-4 sm:gap-6">
                <div class="w-full">
                  <label for="brand" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">ชื่อทริปทัวร์</label>
                  <input type="text" name="brand" id="brand" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500" placeholder="" required="">
              </div>
              <div class="w-full">
                  <label for="brand" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">ชื่อทริปทัวร์</label>
                  <input type="text" name="brand" id="brand" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500" placeholder="" required="">
              </div>
              <div class="w-full">
                  <label for="price" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">ชื่อโปรแกรมทัวร์</label>
                  <input type="number" name="price" id="price" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500" placeholder="" required="">
              </div>
            <div>

                <label for="countries" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">ภาษี (0% 7% 9%)</label>
<select id="countries" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500">
  <option selected></option>
  <option value="US">0%</option>
  <option value="CA">7%</option>
  <option value="FR">9%</option>
</select>
           
        </div>
            </div>
            <div class="grid gap-4 sm:grid-cols-1 sm:gap-6">
          <button type="submit" class= "inline-flex items-center px-5 py-2.5 mt-4 sm:mt-6 text-sm font-medium text-center text-white bg-primary-700 rounded-lg focus:ring-4 focus:ring-primary-200 dark:focus:ring-primary-900 hover:bg-primary-800 bg-blue-500">
             สร้างทัวร์
          </button>
        </div>
      </form>
  </div>
</section>
<section class="bg-white dark:bg-gray-900">
  <div class="py-8 px-1 mx-auto max-w-2xl lg:py-16">
      <h2 class="mb-4 text-xl font-bold text-gray-900 dark:text-white">ข้อมูลโรงแรมที่พัก</h2>
      <form action="#">
          <div class="grid gap-4 sm:grid-cols-1 sm:gap-6">
              <div class="w-full">
                  <label for="brand" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">ชื่อทริปทัวร์</label>
                  <input type="text" name="brand" id="brand" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500" placeholder="" required="">
              </div>
             
            </div>
            <br>
            <div class="grid gap-2 sm:grid-cols-2 sm:gap-2">
              <div class="w-full">
                  <label for="brand" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">จำนวนห้องพัก</label>
                  <input type="text" name="brand" id="brand" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500" placeholder="" required="">
              </div>
              <div class="w-full">
                
                <label for="price" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">ระยะเวลา</label>
                <input type="date" id="start" name="trip-start"
value=""
       min="2023-01-01" max="2023-12-31" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500">
            </div>
         
            <div>
        </div>
          </div>
          <div class="grid gap-4 sm:grid-cols-1 sm:gap-6">
          <button type="submit" class="inline-flex items-center px-5 py-2.5 mt-4 sm:mt-6 text-sm font-medium text-center text-white bg-primary-700 rounded-lg focus:ring-4 focus:ring-primary-200 dark:focus:ring-primary-900 hover:bg-primary-800  bg-blue-500">
           เพิ่มโรงเเรม
          </button>
        </div>
            <br>
            <div class="grid gap-4 sm:grid-cols-4 sm:gap-6">
            <div>
        </div>
            </div>
            
<div class="relative overflow-x-auto">
    <table class="w-full text-sm text-left text-gray-500 dark:text-gray-400">
        <thead class="text-xs text-gray-700 uppercase bg-gray-50 dark:bg-gray-700 dark:text-gray-400">
            <tr>
                <th scope="col" class="px-6 py-3">
                  ชื่อโรงเเรม
                </th>
                <th scope="col" class="px-6 py-3">
                    จํานวนห้องพัก
                </th>
                <th scope="col" class="px-6 py-3">
                   วันเช็คอินน์
                </th>
                <th scope="col" class="px-6 py-3">
                    วันเช็คเอ้าท์
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

            <div class="grid gap-4 sm:grid-cols-5 sm:gap-6">
          <button type="submit" class="inline-flex items-center px-5 py-2.5 mt-4 sm:mt-6 text-sm font-medium text-center text-white bg-primary-700 rounded-lg focus:ring-4 focus:ring-primary-200 dark:focus:ring-primary-900 hover:bg-primary-800">
            บันทึกข้อมูล
          </button>
        </div>
      </form>
  </div>
</section>
</div>

  </template>
  