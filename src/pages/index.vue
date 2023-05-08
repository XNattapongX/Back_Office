<template>
  <!-- First code -->
  <br>
  <div class="bg-green-50 dark:bg-gray-800 relative px-3 shadow-lg sm:rounded-lg overflow-hidden">
      <div class="flex flex-col md:flex-row items-center justify-between space-y-3 md:space-y-0 md:space-x-4 p-4">
          <div class="w-full md:w-1/2">
              <form class="flex items-center">
                  <label for="simple-search" class="sr-only">ค้นหาข้อมูลทัวร์</label>
                  <div class="relative w-full">
                      <div class="absolute inset-y-0 left-0 flex items-center pl-3 pointer-events-none">
                          <svg aria-hidden="true" class="w-5 h-5 text-gray-500 dark:text-gray-400" fill="currentColor"
                              viewbox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                              <path fill-rule="evenodd"
                                  d="M8 4a4 4 0 100 8 4 4 0 000-8zM2 8a6 6 0 1110.89 3.476l4.817 4.817a1 1 0 01-1.414 1.414l-4.816-4.816A6 6 0 012 8z"
                                  clip-rule="evenodd" />
                          </svg>
                      </div>
                      <input type="text" id="simple-search"
                          class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-500 focus:border-primary-500 block w-full pl-10 p-2 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500"
                          placeholder="ค้นหาข้อมูลทัวร์">
                  </div>
              </form>
          </div>
          <div
              class="w-full md:w-auto flex flex-col md:flex-row space-y-2 md:space-y-0 items-stretch md:items-center justify-end md:space-x-3 flex-shrink-0">
              <button type="button"
                  class="flex items-center justify-center text-white bg-primary-700 hover:bg-primary-800 focus:ring-4 focus:ring-primary-300 font-medium rounded-lg text-sm px-4 py-2 dark:bg-primary-600 dark:hover:bg-primary-700 focus:outline-none dark:focus:ring-primary-800">
                  <a href="addtour"> สร้างทัวร์</a>
              </button>
          </div>
      </div>
  </div>
  <br>
  <!-- First code -->

  <!-- second code -->
  <div class="relative overflow-x-auto shadow-md sm:rounded-lg">
      <table class="w-full text-sm text-left text-gray-500 dark:text-gray-400">
          <thead class="text-xs text-white uppercase bg-blue-400 dark:bg-gray-700 dark:text-gray-400">
              <tr>
                  <th scope="col" class="px-6 py-3">
                      ชื่อทริปทัวร์
                  </th>
                  <th scope="col" class="px-6 py-3">
                      ชื่อโปรแกรมทัวร์
                  </th>
                  <th scope="col" class="px-6 py-3">
                      วันที่เริ่มทริป
                  </th>
                  <th scope="col" class="px-6 py-3">
                      วันที่จบทริป
                  </th>
                  <th scope="col" class="px-6 py-3">
                      วัน
                  </th>
                  <th scope="col" class="px-6 py-3">
                      คืน
                  </th>
                  <th scope="col" class="px-6 py-3">
                      เที่ยวบินหรือพาหนะอื่นขาไป
                  </th>
                  <th scope="col" class="px-6 py-3">
                      เที่ยวบินหรือพาหนะอื่นขากลับ
                  </th>
                  <th scope="col" class="px-6 py-3">
                      จำนวนลูกทัวร์
                  </th>
                  <th scope="col" class="px-6 py-3">
                      รายละเอียดทัวร์
                  </th>
              </tr>
          </thead>

          <tbody>
              <tr class="bg-white border-b dark:bg-gray-800 dark:border-gray-700 hover:bg-gray-50 dark:hover:bg-gray-600">
                  <td class="px-6 py-4">
                      เที่ยวเกาะเลาะรัก
                  </td>
                  <td class="px-6 py-4">
                      เกาะเสม็ดเสร็จทุกราย
                  </td>
                  <td class="px-6 py-4">
                      16/04/2566
                  </td>
                  <td class="px-6 py-4">
                      20/04/2566
                  </td>
                  <td class="px-6 py-4">
                      5
                  </td>
                  <td class="px-6 py-4">
                      4
                  </td>
                  <td class="px-6 py-4">
                      นครชัยแอร์
                  </td>
                  <td class="px-6 py-4">
                      AirAsia
                  </td>
                  <td class="px-6 py-4">
                      1
                  </td>
                  <td class="px-6 py-4">
                      <button type="button"
                          class="focus:outline-none text-white bg-green-700 hover:bg-green-800 focus:ring-4 focus:ring-green-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-green-600 dark:hover:bg-green-700 dark:focus:ring-green-800"
                          onclick="location.href='tour_is_detail'">รายละเอียดทัวร์</button>
                  </td>
              </tr>
              <tr class="bg-white border-b dark:bg-gray-800 dark:border-gray-700 hover:bg-gray-50 dark:hover:bg-gray-600">
                  <td class="px-6 py-4">
                      องค์การบริหารส่วนตำบลโพนงาม
                  </td>
                  <td class="px-6 py-4">
                      กาญจนบุรี-เพชรบุรี
                  </td>
                  <td class="px-6 py-4">
                      29/03/2566
                  </td>
                  <td class="px-6 py-4">
                      01/04/2566
                  </td>
                  <td class="px-6 py-4">
                      4
                  </td>
                  <td class="px-6 py-4">
                      2
                  </td>
                  <td class="px-6 py-4">
                      รถทัวร์นิลผกา 1-พิกุล 2
                  </td>
                  <td class="px-6 py-4">
                      รถทัวร์นิลผกา 1-พิกุล 2
                  </td>
                  <td class="px-6 py-4">
                      0
                  </td>
                  <td class="px-6 py-4">
                      <button type="button"
                          class="focus:outline-none text-white bg-green-700 hover:bg-green-800 focus:ring-4 focus:ring-green-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-green-600 dark:hover:bg-green-700 dark:focus:ring-green-800"
                          onclick="location.href='tour_is_detail'">รายละเอียดทัวร์</button>
                  </td>
              </tr>
              <tr class="bg-white border-b dark:bg-gray-800 dark:border-gray-700 hover:bg-gray-50 dark:hover:bg-gray-600">
                  <td class="px-6 py-4">
                      เกาะล้าน
                  </td>
                  <td class="px-6 py-4">
                      เที่ยว 10 จ่าย 8
                  </td>
                  <td class="px-6 py-4">
                      16/04/2566
                  </td>
                  <td class="px-6 py-4">
                      23/04/2566
                  </td>
                  <td class="px-6 py-4">
                      10
                  </td>
                  <td class="px-6 py-4">
                      8
                  </td>
                  <td class="px-6 py-4">
                      รถตู้
                  </td>
                  <td class="px-6 py-4">
                      รถทัวร์
                  </td>
                  <td class="px-6 py-4">
                      1
                  </td>
                  <td class="px-6 py-4">
                      <button type="button"
                          class="focus:outline-none text-white bg-green-700 hover:bg-green-800 focus:ring-4 focus:ring-green-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-green-600 dark:hover:bg-green-700 dark:focus:ring-green-800"
                          onclick="location.href='tour_is_detail'">รายละเอียดทัวร์</button>
                  </td>
              </tr>
              <tr class="bg-white border-b dark:bg-gray-800 dark:border-gray-700 hover:bg-gray-50 dark:hover:bg-gray-600">
                  <td class="px-6 py-4">
                      อุบล
                  </td>
                  <td class="px-6 py-4">
                      โขงเจียม-วัดถ้ำคูหาสวรรค์
                  </td>
                  <td class="px-6 py-4">
                      12/04/2566
                  </td>
                  <td class="px-6 py-4">
                      14/04/2566
                  </td>
                  <td class="px-6 py-4">
                      3
                  </td>
                  <td class="px-6 py-4">
                      2
                  </td>
                  <td class="px-6 py-4">
                      รถยนต์
                  </td>
                  <td class="px-6 py-4">
                      รถยนต์
                  </td>
                  <td class="px-6 py-4">
                      3
                  </td>
                  <td class="px-6 py-4">
                      <button type="button"
                          class="focus:outline-none text-white bg-green-700 hover:bg-green-800 focus:ring-4 focus:ring-green-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-green-600 dark:hover:bg-green-700 dark:focus:ring-green-800"
                          onclick="location.href='tour_is_detail'">รายละเอียดทัวร์</button>
                  </td>
              </tr>
      </tbody>
  </table>
</div>
<!-- second code --></template>