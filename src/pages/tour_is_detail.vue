<template>
  <div class="relative overflow-x-auto">
    <table class="w-full text-sm text-left text-gray-500 dark:text-gray-400">
      <tbody>
        <tr class="bg-blue-100 dark:bg-gray-800">
          <td class="px-6 py-2">
            ชื่อทริปทัวร์ : อุบล
          </td>
          <td class="px-6 py-2">

          </td>
          <td class="px-6 py-2">
            ชื่อไกด์ : เหนือ
          </td>
          <td class="px-6 py-2">
            เบอร์โทร : 0661242478
          </td>
        </tr>
        <tr class="bg-blue-100 dark:bg-gray-800">
          <td class="px-6 py-2">
            โปรแกรมทัวร์ : โขงเจียม-วัดถ้ำคูหาสวรรค์
          </td>
          <td class="px-6 py-2">
            จำนวน : 3 วัน 2 คืน
          </td>
          <td class="px-6 py-2">
            วันที่เดือนปี 12/04/2566 ถึง 12/04/2566
          </td>
          <td class="px-6 py-2">
            จำนวนลูกทัวร์ : 1
          </td>
        </tr>
        <tr class="bg-yellow-100 dark:bg-gray-800">
          <td class="px-6 py-2">
            ชื่อโรงแรม : motal
          </td>
          <td class="px-6 py-2">
            จำนวนห้องพัก : 10
          </td>
          <td class="px-6 py-2">
            วันที่เช็คอินน์ : 12/04/2566
          </td>
          <td class="px-6 py-2">
            วันที่เช็คเอ้าท์ : 14/04/2566
          </td>
        </tr>
        <tr class="bg-blue-100 dark:bg-gray-800">
          <td class="px-6 py-2">
            เที่ยวบินหรือพาหนะอื่นๆ ขาไป : รถยนต์
          </td>
          <td class="px-6 py-2">

          </td>
          <td class="px-6 py-2">
            เที่ยวบินหรือพาหนะอื่นๆ ขากลับ : รถยนต์
          </td>
          <td class="px-6 py-2">
            หมายเหตุ :
          </td>
        </tr>
      </tbody>
    </table>
  </div>


  <!-- second code -->
  <div class="mb-127 relative overflow-x-auto shadow-md">
    <table class="w-full text-sm text-left text-gray-500 dark:text-gray-400">
      <thead class="text-xs text-white uppercase bg-blue-400 dark:bg-gray-700 dark:text-gray-400">
        <tr>
          <th scope="col" class="px-6 py-3">
            ลำดับ
          </th>
          <th scope="col" class="px-6 py-3">
            ชื่อ-นามสกุล ภาษาไทย
          </th>
          <th scope="col" class="px-6 py-3">
            หมายเลขบัตรประชาชน
          </th>
          <th scope="col" class="px-6 py-3">
            ชื่อ-นามสกุล ภาษาอังกฤษ
          </th>
          <th scope="col" class="px-6 py-3">
            หมายเลขพาสปอร์ต
          </th>
          <th scope="col" class="px-6 py-3">
            สัญชาติ
          </th>
          <th scope="col" class="px-6 py-3">
            เพศ
          </th>
          <th scope="col" class="px-6 py-3">
            ประเภทเตียง
          </th>
          <th scope="col" class="px-6 py-3">
            เพิ่มเติม
          </th>
        </tr>
      </thead>

      <tbody>
        <tr class="bg-white border-b dark:bg-gray-800 dark:border-gray-700 hover:bg-gray-50 dark:hover:bg-gray-600">
          <td class="px-6 py-3">
            1
          </td>
          <td class="px-6 py-3">
            ขยัน ขันแข็ง
          </td>
          <td class="px-6 py-3">
            3256489512365
          </td>
          <td class="px-6 py-3">
            Kayan Kankhang
          </td>
          <td class="px-6 py-3">
            8777/8
          </td>
          <td class="px-6 py-3">
            8
          </td>
          <td class="px-6 py-3">
            ชาย
          </td>
          <td class="px-6 py-3">
            คู่
          </td>
          <td class="px-6 py-3">

            <!-- Modal toggle -->
            <button data-modal-target="staticModal" data-modal-toggle="staticModal"
              class="focus:outline-none text-white bg-green-300 hover:bg-green-800 focus:ring-4 focus:ring-green-300 font-medium font-weight-bold rounded-lg text-sm text-green-700 px-5 py-2.5 mr-2 mb-2 dark:bg-green-600 dark:hover:bg-green-700 dark:focus:ring-green-800"
              type="button">
              รายละเอียดลูกทัวร์
            </button>

            <!-- Main modal -->
            <div id="staticModal" data-modal-backdrop="static" tabindex="-1" aria-hidden="true"
              class="fixed top-0 left-0 right-0 z-50 hidden w-full p-4 overflow-x-hidden overflow-y-auto md:inset-0 h-[calc(100%-1rem)] max-h-full">
              <div class="relative w-full max-w-2xl max-h-full">
                <!-- Modal content -->
                <div class="relative bg-white rounded-lg shadow-lg dark:bg-gray-700">
                  <!-- Modal header -->
                  <div class="flex items-start justify-between p-4 border-b rounded-t dark:border-gray-600">
                    <h3 class="text-xl font-semibold text-gray-900 dark:text-white">
                      รายละเอียดลูกทัวร์ : นายพชร เพียซ้าย
                    </h3>
                    <button type="button"
                      class="text-gray-400 bg-transparent hover:bg-gray-200 hover:text-gray-900 rounded-lg text-sm p-1.5 ml-auto inline-flex items-center dark:hover:bg-gray-600 dark:hover:text-white"
                      data-modal-hide="staticModal">
                      <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                        <path fill-rule="evenodd"
                          d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z"
                          clip-rule="evenodd"></path>
                      </svg>
                    </button>
                  </div>
                  <!-- Modal body -->
                  <div class="p-6 space-y-6">
                    <p class="text-base leading-relaxed text-gray-500 dark:text-gray-400">
                      วันที่ออกพาสปอร์ต: 25/03/2566
                      <br>
                      วันหมดอายุพาสปอร์ต: 12/04/2566
                      <br>
                      วันเดือนปีเกิด: 24/07/2543
                      <br>
                      ตรวจลงตราเลขที: -
                      <br>
                      หมายเหตุ: -
                    </p>
                  </div>
                  <!-- Modal footer -->
                  <div class="flex items-center p-6 space-x-2 border-t border-gray-200 rounded-b dark:border-gray-600">


                    <form>
                      <label for="default-search"
                        class="mb-2 text-sm font-medium text-gray-900 sr-only dark:text-white">Comment</label>
                      <div class="relative ">
                        <input type="search" id="default-search"
                          class="block w-75 p-4 pl-10 text-sm text-gray-900 border border-gray-300 rounded-lg bg-gray-50 focus:ring-blue-500 focus:border-blue-500 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                          placeholder="รายละเอียดเพิ่มเติม" required>
                        <button type="submit"
                          class="text-white absolute right-2.5 bottom-2.5 bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-4 py-2 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">คอมเมนต์</button>
                      </div>
                    </form>
                    <div class="relative ">
                      <button type="button"
                        class="focus:outline-none text-white bg-red-700 hover:bg-red-800 focus:ring-4 focus:ring-red-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-red-600 dark:hover:bg-red-700 dark:focus:ring-red-900">ปิด</button>
                    </div>
                  </div>
                </div>
              </div>
            </div>

          </td>
        </tr>

        <tr class="bg-white border-b dark:bg-gray-800 dark:border-gray-700 hover:bg-gray-50 dark:hover:bg-gray-600">
          <td class="px-6 py-3">
            1
          </td>
          <td class="px-6 py-3">
            ขยัน ขันแข็ง
          </td>
          <td class="px-6 py-3">
            3256489512365
          </td>
          <td class="px-6 py-3">
            Kayan Kankhang
          </td>
          <td class="px-6 py-3">
            8777/8
          </td>
          <td class="px-6 py-3">
            8
          </td>
          <td class="px-6 py-3">
            ชาย
          </td>
          <td class="px-6 py-3">
            คู่
          </td>
          <td class="px-6 py-3">

            <!-- Modal toggle -->
            <button data-modal-target="staticModal" data-modal-toggle="staticModal"
              class="focus:outline-none text-white bg-green-300 hover:bg-green-800 focus:ring-4 focus:ring-green-300 font-medium font-weight-bold rounded-lg text-sm text-green-700 px-5 py-2.5 mr-2 mb-2 dark:bg-green-600 dark:hover:bg-green-700 dark:focus:ring-green-800"
              type="button">
              รายละเอียดลูกทัวร์
            </button>

            <!-- Main modal -->
            <div id="staticModal" data-modal-backdrop="static" tabindex="-1" aria-hidden="true"
              class="fixed top-0 left-0 right-0 z-50 hidden w-full p-4 overflow-x-hidden overflow-y-auto md:inset-0 h-[calc(100%-1rem)] max-h-full">
              <div class="relative w-full max-w-2xl max-h-full">
                <!-- Modal content -->
                <div class="relative bg-white rounded-lg shadow-lg dark:bg-gray-700">
                  <!-- Modal header -->
                  <div class="flex items-start justify-between p-4 border-b rounded-t dark:border-gray-600">
                    <h3 class="text-xl font-semibold text-gray-900 dark:text-white">
                      รายละเอียดลูกทัวร์ : นายพชร เพียซ้าย
                    </h3>
                    <button type="button"
                      class="text-gray-400 bg-transparent hover:bg-gray-200 hover:text-gray-900 rounded-lg text-sm p-1.5 ml-auto inline-flex items-center dark:hover:bg-gray-600 dark:hover:text-white"
                      data-modal-hide="staticModal">
                      <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                        <path fill-rule="evenodd"
                          d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z"
                          clip-rule="evenodd"></path>
                      </svg>
                    </button>
                  </div>
                  <!-- Modal body -->
                  <div class="p-6 space-y-6">
                    <p class="text-base leading-relaxed text-gray-500 dark:text-gray-400">
                      วันที่ออกพาสปอร์ต: 25/03/2566
                      <br>
                      วันหมดอายุพาสปอร์ต: 12/04/2566
                      <br>
                      วันเดือนปีเกิด: 24/07/2543
                      <br>
                      ตรวจลงตราเลขที: -
                      <br>
                      หมายเหตุ: -
                    </p>
                  </div>
                  <!-- Modal footer -->
                  <div class="flex items-center p-6 space-x-2 border-t border-gray-200 rounded-b dark:border-gray-600">


                    <form>
                      <label for="default-search"
                        class="mb-2 text-sm font-medium text-gray-900 sr-only dark:text-white">Comment</label>
                      <div class="relative ">
                        <input type="search" id="default-search"
                          class="block w-75 p-4 pl-10 text-sm text-gray-900 border border-gray-300 rounded-lg bg-gray-50 focus:ring-blue-500 focus:border-blue-500 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                          placeholder="รายละเอียดเพิ่มเติม" required>
                        <button type="submit"
                          class="text-white absolute right-2.5 bottom-2.5 bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-4 py-2 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">คอมเมนต์</button>
                      </div>
                    </form>
                    <div class="relative ">
                      <button type="button"
                        class="focus:outline-none text-white bg-red-700 hover:bg-red-800 focus:ring-4 focus:ring-red-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-red-600 dark:hover:bg-red-700 dark:focus:ring-red-900">ปิด</button>
                    </div>
                  </div>
                </div>
              </div>
            </div>

          </td>
        </tr>
      </tbody>
    </table>
  </div>

  <footer class="footer bg-white flex-row items-center justify-center shadow dark:bg-gray-900">
    <div class="ml-160 flex-row items-center justify-center max-w-screen-xl px-0 py-2">
      <div class="sm:flex sm:items-center sm:justify-between">
        <button data-modal-target="popup-modal" data-modal-toggle="popup-modal"
          class="focus:outline-none text-red-600 bg-red-200 hover:bg-red-800 focus:ring-4 focus:ring-red-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-red-600 dark:hover:bg-red-700 dark:focus:ring-red-900"
          type="button">
          ลบทัวร์
        </button>

        <div id="popup-modal" tabindex="-1"
          class="fixed top-0 left-0 right-0 z-50 hidden p-4 overflow-x-hidden overflow-y-auto md:inset-0 h-[calc(100%-1rem)] max-h-full">
          <div class="relative w-full max-w-md max-h-full">
            <div class="relative bg-white rounded-lg shadow-lg dark:bg-gray-700">
              <button type="button"
                class="absolute top-3 right-2.5 text-gray-400 bg-transparent hover:bg-gray-200 hover:text-gray-900 rounded-lg text-sm p-1.5 ml-auto inline-flex items-center dark:hover:bg-gray-800 dark:hover:text-white"
                data-modal-hide="popup-modal">
                <svg aria-hidden="true" class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20"
                  xmlns="http://www.w3.org/2000/svg">
                  <path fill-rule="evenodd"
                    d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z"
                    clip-rule="evenodd"></path>
                </svg>
                <span class="sr-only">ต้องการลบข้อมูลหรือไม่?</span>
              </button>
              <div class="p-6 text-center">
                <svg aria-hidden="true" class="mx-auto mb-4 text-gray-400 w-14 h-14 dark:text-gray-200" fill="none"
                  stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                    d="M12 8v4m0 4h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z"></path>
                </svg>
                <h3 class="mb-5 text-lg font-normal text-gray-500 dark:text-gray-400">ยืนยันการลบข้อมูล</h3>
                <button data-modal-hide="popup-modal" type="button"
                  class="text-red-600 bg-red-200 hover:bg-red-800 focus:ring-4 focus:outline-none focus:ring-red-300 dark:focus:ring-red-800 font-medium rounded-lg text-sm inline-flex items-center px-5 py-2.5 text-center mr-2">
                  ยืนยัน
                </button>
                <button data-modal-hide="popup-modal" type="button"
                  class="text-gray-500 bg-white hover:bg-gray-100 focus:ring-4 focus:outline-none focus:ring-gray-200 rounded-lg border border-gray-200 text-sm font-medium px-5 py-2.5 hover:text-gray-900 focus:z-10 dark:bg-gray-700 dark:text-gray-300 dark:border-gray-500 dark:hover:text-white dark:hover:bg-gray-600 dark:focus:ring-gray-600">
                  ยกเลิก</button>
              </div>
            </div>
          </div>
        </div>

        <ul class="flex flex-wrap items-center mb-6 text-sm font-medium text-gray-500 sm:mb-0 dark:text-gray-400">
          <li>
            <button data-modal-target="staticModal1" data-modal-toggle="staticModal1"
              class="focus:outline-none text-green-600 bg-green-100 hover:bg-green-800 focus:ring-4 focus:ring-green-300 font-medium font-weight-bold rounded-lg text-sm text-white px-5 py-2.5 mr-2 mb-2 dark:bg-green-600 dark:hover:bg-green-700 dark:focus:ring-green-800"
              type="button">
              จัดการร้านอาหาร
            </button>

            <!-- Main modal -->
            <div id="staticModal1" data-modal-backdrop="static1" tabindex="-1" aria-hidden="true"
              class="fixed top-0 left-0 right-0 z-50 hidden w-full p-4 overflow-x-hidden overflow-y-auto md:inset-0 h-[calc(100%-1rem)] max-h-full">
              <div class="relative w-full max-w-2xl max-h-full">
                <!-- Modal content -->
                <div class="relative bg-white rounded-lg shadow-lg dark:bg-gray-700">
                  <!-- Modal header -->
                  <div class="flex items-start justify-between p-4 border-b rounded-t dark:border-gray-600">

                    <form>
                      <label for="default-search"
                        class="mb-2 text-sm font-medium text-gray-900 sr-only dark:text-white">Search</label>
                      <div class="relative">
                        <div class="absolute inset-y-0 left-0 flex items-center pl-3 pointer-events-none">
                          <svg aria-hidden="true" class="w-5 h-5 text-gray-500 dark:text-gray-400" fill="none"
                            stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                              d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"></path>
                          </svg>
                        </div>
                        <input type="search" id="default-search"
                          class="block w-150 p-4 pl-10 text-sm text-gray-900 border border-gray-300 rounded-lg bg-gray-50 focus:ring-blue-500 focus:border-blue-500 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                          placeholder="ชื่อร้านอาหาร" required>
                        <button type="submit"
                          class="text-white absolute right-2.5 bottom-2.5 bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-4 py-2 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">เพิ่ม</button>
                      </div>
                    </form>

                    <button type="button"
                      class="text-gray-400 bg-transparent hover:bg-gray-200 hover:text-gray-900 rounded-lg text-sm p-1.5 ml-auto inline-flex items-center dark:hover:bg-gray-600 dark:hover:text-white"
                      data-modal-hide="staticModal1">
                      <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                        <path fill-rule="evenodd"
                          d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z"
                          clip-rule="evenodd"></path>
                      </svg>
                    </button>
                  </div>
                  <!-- Modal body -->
                  <div class="p-6 space-y-6">
                    <h3 class="flex-row items-center justify-center text-xl  font-semibold text-gray-900 dark:text-white">
                      รายการร้านอาหาร
                    </h3>
                    <table class="w-full text-sm text-center text-gray-500 dark:text-gray-400">
                      <thead class="text-xs text-white uppercase bg-green-400 dark:bg-gray-700 dark:text-gray-400">
                        <tr>
                          <th scope="col" class="px-2 py-2">
                            ร้าน
                          </th>
                          <th scope="col" class="px-2 py-2">
                            คอมเมนต์
                          </th>
                          <th scope="col" class="px-2 py-2">
                            จังหวัด
                          </th>
                        </tr>
                      </thead>
                      <tbody>
                        <tr
                          class="bg-white border-b dark:bg-gray-800 dark:border-gray-700 hover:bg-gray-50 dark:hover:bg-gray-600">
                          <td class="px-2 py-2">
                            ร้านแตงไทย
                          </td>
                          <td class="px-2 py-2">
                            อร่อยดี
                          </td>
                          <td class="px-6 py-3">
                            จันทบุรี
                          </td>
                        </tr>
                        <tr
                          class="bg-white border-b dark:bg-gray-800 dark:border-gray-700 hover:bg-gray-50 dark:hover:bg-gray-600">
                          <td class="px-2 py-2">
                            ร้านกวา
                          </td>
                          <td class="px-2 py-2">
                            แซ่บอิหลี
                          </td>
                          <td class="px-6 py-3">
                            ประจวบคีรีขันธ์
                          </td>
                        </tr>
                      </tbody>
                    </table>
                  </div>
                  <!-- Modal footer -->
                  <div class="flex items-center p-6 space-x-2 border-t border-gray-200 rounded-b dark:border-gray-600">
                    <div class="relative ">
                      <button type="button"
                        class="focus:outline-none text-white bg-red-700 hover:bg-red-800 focus:ring-4 focus:ring-red-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-red-600 dark:hover:bg-red-700 dark:focus:ring-red-900">ปิด</button>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </li>

          <li>
            <button data-modal-target="staticModal2" data-modal-toggle="staticModal2"
              class="focus:outline-none text-green-600 bg-green-100 hover:bg-green-800 focus:ring-4 focus:ring-green-300 font-medium font-weight-bold rounded-lg text-sm text-white px-5 py-2.5 mr-2 mb-2 dark:bg-green-600 dark:hover:bg-green-700 dark:focus:ring-green-800"
              type="button">
              จัดการสถานที่ท่องเที่ยว
            </button>

            <!-- Main modal -->
            <div id="staticModal2" data-modal-backdrop="static2" tabindex="-1" aria-hidden="true"
              class="fixed top-0 left-0 right-0 z-50 hidden w-full p-4 overflow-x-hidden overflow-y-auto md:inset-0 h-[calc(100%-1rem)] max-h-full">
              <div class="relative w-full max-w-2xl max-h-full">
                <!-- Modal content -->
                <div class="relative bg-white rounded-lg shadow-lg dark:bg-gray-700">
                  <!-- Modal header -->
                  <div class="flex items-start justify-between p-4 border-b rounded-t dark:border-gray-600">

                    <form>
                      <label for="default-search"
                        class="mb-2 text-sm font-medium text-gray-900 sr-only dark:text-white">Search</label>
                      <div class="relative">
                        <div class="absolute inset-y-0 left-0 flex items-center pl-3 pointer-events-none">
                          <svg aria-hidden="true" class="w-5 h-5 text-gray-500 dark:text-gray-400" fill="none"
                            stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                              d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"></path>
                          </svg>
                        </div>
                        <input type="search" id="default-search"
                          class="block w-150 p-4 pl-10 text-sm text-gray-900 border border-gray-300 rounded-lg bg-gray-50 focus:ring-blue-500 focus:border-blue-500 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                          placeholder="ชื่อสถานที่ท่องเที่ยว" required>
                        <button type="submit"
                          class="text-white absolute right-2.5 bottom-2.5 bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-4 py-2 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">เพิ่ม</button>
                      </div>
                    </form>

                    <button type="button"
                      class="text-gray-400 bg-transparent hover:bg-gray-200 hover:text-gray-900 rounded-lg text-sm p-1.5 ml-auto inline-flex items-center dark:hover:bg-gray-600 dark:hover:text-white"
                      data-modal-hide="staticModal2">
                      <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                        <path fill-rule="evenodd"
                          d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z"
                          clip-rule="evenodd"></path>
                      </svg>
                    </button>
                  </div>
                  <!-- Modal body -->
                  <div class="p-6 space-y-6">
                    <h3 class="flex-row items-center justify-center text-xl  font-semibold text-gray-900 dark:text-white">
                      รายการท่องเที่ยว
                    </h3>
                    <table class="w-full text-sm text-center text-gray-500 dark:text-gray-400">
                      <thead class="text-xs text-white uppercase bg-green-400 dark:bg-gray-700 dark:text-gray-400">
                        <tr>
                          <th scope="col" class="px-2 py-2">
                            สถานที่เที่ยว
                          </th>
                          <th scope="col" class="px-2 py-2">
                            คอมเมนต์
                          </th>
                          <th scope="col" class="px-2 py-2">
                            จังหวัด
                          </th>
                        </tr>
                      </thead>
                      <tbody>
                        <tr
                          class="bg-white border-b dark:bg-gray-800 dark:border-gray-700 hover:bg-gray-50 dark:hover:bg-gray-600">
                          <td class="px-2 py-2">
                            เขาใหญ่
                          </td>
                          <td class="px-2 py-2">
                            อบอุ่นดี
                          </td>
                          <td class="px-6 py-3">
                            นครราชสีมา
                          </td>
                        </tr>
                        <tr
                          class="bg-white border-b dark:bg-gray-800 dark:border-gray-700 hover:bg-gray-50 dark:hover:bg-gray-600">
                          <td class="px-2 py-2">
                            ภูเขียว
                          </td>
                          <td class="px-2 py-2">
                            ทะเลหมอก
                          </td>
                          <td class="px-6 py-3">
                            ชัยภูมิ
                          </td>
                        </tr>
                      </tbody>
                    </table>
                  </div>
                  <!-- Modal footer -->
                  <div class="flex items-center p-6 space-x-2 border-t border-gray-200 rounded-b dark:border-gray-600">
                    <div class="relative ">
                      <button type="button"
                        class="focus:outline-none text-white bg-red-700 hover:bg-red-800 focus:ring-4 focus:ring-red-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-red-600 dark:hover:bg-red-700 dark:focus:ring-red-900">ปิด</button>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </li>

          <li>
            <button data-modal-target="staticModa3" data-modal-toggle="staticModal3"
              class="focus:outline-none text-green-600 bg-green-100 hover:bg-green-800 focus:ring-4 focus:ring-green-300 font-medium font-weight-bold rounded-lg text-sm text-white px-5 py-2.5 mr-2 mb-2 dark:bg-green-600 dark:hover:bg-green-700 dark:focus:ring-green-800"
              type="button">
              จัดการเส้นทาง
            </button>

            <!-- Main modal -->
            <div id="staticModal3" data-modal-backdrop="static3" tabindex="-1" aria-hidden="true"
              class="fixed top-0 left-0 right-0 z-50 hidden w-full p-4 overflow-x-hidden overflow-y-auto md:inset-0 h-[calc(100%-1rem)] max-h-full">
              <div class="relative w-full max-w-2xl max-h-full">
                <!-- Modal content -->
                <div class="relative bg-white rounded-lg shadow-lg dark:bg-gray-700">
                  <!-- Modal header -->
                  <div class="flex items-start justify-between p-4 border-b rounded-t dark:border-gray-600">

                    <form>
                      <label for="default-search"
                        class="mb-2 text-sm font-medium text-gray-900 sr-only dark:text-white">Search</label>
                      <div class="relative">
                        <div class="absolute inset-y-0 left-0 flex items-center pl-3 pointer-events-none">
                          <svg aria-hidden="true" class="w-5 h-5 text-gray-500 dark:text-gray-400" fill="none"
                            stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                              d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"></path>
                          </svg>
                        </div>
                        <input type="search" id="default-search"
                          class="block w-150 p-4 pl-10 text-sm text-gray-900 border border-gray-300 rounded-lg bg-gray-50 focus:ring-blue-500 focus:border-blue-500 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                          placeholder="ชื่อเส้นทาง" required>
                        <button type="submit"
                          class="text-white absolute right-2.5 bottom-2.5 bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-4 py-2 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">เพิ่ม</button>
                      </div>
                    </form>

                    <button type="button"
                      class="text-gray-400 bg-transparent hover:bg-gray-200 hover:text-gray-900 rounded-lg text-sm p-1.5 ml-auto inline-flex items-center dark:hover:bg-gray-600 dark:hover:text-white"
                      data-modal-hide="staticModal3">
                      <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                        <path fill-rule="evenodd"
                          d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z"
                          clip-rule="evenodd"></path>
                      </svg>
                    </button>
                  </div>
                  <!-- Modal body -->
                  <div class="p-6 space-y-6">
                    <h3 class="flex-row items-center justify-center text-xl  font-semibold text-gray-900 dark:text-white">
                      จัดการเส้นทาง
                    </h3>
                    <table class="w-full text-sm text-center text-gray-500 dark:text-gray-400">
                      <thead class="text-xs text-white uppercase bg-green-400 dark:bg-gray-700 dark:text-gray-400">
                        <tr>
                          <th scope="col" class="px-2 py-2">
                            เส้นทางเดินทาง
                          </th>
                          <th scope="col" class="px-2 py-2">
                            คอมเมนต์
                          </th>
                          <th scope="col" class="px-2 py-2">
                            จังหวัด
                          </th>
                        </tr>
                      </thead>
                      <tbody>
                        <tr
                          class="bg-white border-b dark:bg-gray-800 dark:border-gray-700 hover:bg-gray-50 dark:hover:bg-gray-600">
                          <td class="px-2 py-2">
                            เขาใหญ่
                          </td>
                          <td class="px-2 py-2">
                            อบอุ่นดี
                          </td>
                          <td class="px-6 py-3">
                            นครราชสีมา
                          </td>
                        </tr>
                        <tr
                          class="bg-white border-b dark:bg-gray-800 dark:border-gray-700 hover:bg-gray-50 dark:hover:bg-gray-600">
                          <td class="px-2 py-2">
                            ภูเขียว
                          </td>
                          <td class="px-2 py-2">
                            ทะเลหมอก
                          </td>
                          <td class="px-6 py-3">
                            ชัยภูมิ
                          </td>
                        </tr>
                      </tbody>
                    </table>
                  </div>
                  <!-- Modal footer -->
                  <div class="flex items-center p-6 space-x-2 border-t border-gray-200 rounded-b dark:border-gray-600">
                    <div class="relative ">
                      <button type="button"
                        class="focus:outline-none text-white bg-red-700 hover:bg-red-800 focus:ring-4 focus:ring-red-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-red-600 dark:hover:bg-red-700 dark:focus:ring-red-900">ปิด</button>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </li>

          <li>
            <button data-modal-target="staticModal4" data-modal-toggle="staticModal4"
              class="focus:outline-none text-green-600 bg-green-100 hover:bg-green-800 focus:ring-4 focus:ring-green-300 font-medium font-weight-bold rounded-lg text-sm text-white px-5 py-2.5 mr-2 mb-2 dark:bg-green-600 dark:hover:bg-green-700 dark:focus:ring-green-800"
              type="button">
              คอมเม้นโรงแรม
            </button>

            <!-- Main modal -->
            <div id="staticModal4" data-modal-backdrop="static4" tabindex="-1" aria-hidden="true"
              class="fixed top-0 left-0 right-0 z-50 hidden w-full p-4 overflow-x-hidden overflow-y-auto md:inset-0 h-[calc(100%-1rem)] max-h-full">
              <div class="relative w-full max-w-2xl max-h-full">
                <!-- Modal content -->
                <div class="relative bg-white rounded-lg shadow-lg dark:bg-gray-700">
                  <!-- Modal header -->
                  <div class="flex items-start justify-between p-4 border-b rounded-t dark:border-gray-600">

                    <h3 class="text-xl font-semibold text-gray-900 dark:text-white">
                      คอมเมนต์โรงแรม
                    </h3>

                    <button type="button"
                      class="text-gray-400 bg-transparent hover:bg-gray-200 hover:text-gray-900 rounded-lg text-sm p-1.5 ml-auto inline-flex items-center dark:hover:bg-gray-600 dark:hover:text-white"
                      data-modal-hide="staticModal4">
                      <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                        <path fill-rule="evenodd"
                          d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z"
                          clip-rule="evenodd"></path>
                      </svg>
                    </button>
                  </div>
                  <!-- Modal body -->
                  <div class="p-6 space-y-6">
                    <table class="w-full text-sm text-center text-gray-500 dark:text-gray-400">
                      <thead class="text-xs text-white uppercase bg-green-400 dark:bg-gray-700 dark:text-gray-400">
                        <tr>
                          <th scope="col" class="px-2 py-2">
                            ชื่อโรงแรม
                          </th>
                          <th scope="col" class="px-2 py-2">
                            คอมเมนต์
                          </th>
                          <th scope="col" class="px-2 py-2">
                            ความพึงพอใจ
                          </th>
                        </tr>
                      </thead>
                      <tbody>
                        <tr
                          class="bg-white border-b dark:bg-gray-800 dark:border-gray-700 hover:bg-gray-50 dark:hover:bg-gray-600">
                          <td class="px-2 py-2">
                            ดิออโรร่า ขอนแก่น
                          </td>
                          <td class="px-2 py-2">
                            เตียงนุ่ม
                          </td>
                          <td class="px-6 py-3">
                            4.5 ดาว
                          </td>
                        </tr>
                        <tr
                          class="bg-white border-b dark:bg-gray-800 dark:border-gray-700 hover:bg-gray-50 dark:hover:bg-gray-600">
                          <td class="px-2 py-2">
                            U เชียงคาน
                          </td>
                          <td class="px-2 py-2">
                            บริการดี
                          </td>
                          <td class="px-6 py-3">
                            4.8ดาว
                          </td>
                        </tr>
                      </tbody>
                    </table>
                  </div>
                  <!-- Modal footer -->
                  <div class="flex items-center p-6 space-x-2 border-t border-gray-200 rounded-b dark:border-gray-600">
                    <div class="relative ">
                      <button type="button"
                        class="focus:outline-none text-white bg-red-700 hover:bg-red-800 focus:ring-4 focus:ring-red-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-red-600 dark:hover:bg-red-700 dark:focus:ring-red-900">ปิด</button>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </li>
          <li>
            <button data-modal-target="staticModal5" data-modal-toggle="staticModal5"
              class="focus:outline-none text-blue-600 bg-blue-100 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 font-medium font-weight-bold rounded-lg text-sm text-white px-5 py-2.5 mr-2 mb-2 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800"
              type="button">
              จัดการใบเบิกค่าใช้จ่าย
            </button>

            <!-- Main modal -->
            <div id="staticModal5" data-modal-backdrop="static5" tabindex="-1" aria-hidden="true"
              class="fixed top-0 left-0 right-0 z-50 hidden w-full p-4 overflow-x-hidden overflow-y-auto md:inset-0 h-[calc(100%-1rem)] max-h-full">
              <div class="relative w-full max-w-2xl max-h-full">
                <!-- Modal content -->
                <div class="relative bg-white rounded-lg shadow-lg dark:bg-gray-700">
                  <!-- Modal header -->
                  <div class="flex items-start justify-between p-4 border-b rounded-t dark:border-gray-600">

                    <h3 class="text-xl font-semibold text-gray-900 dark:text-white">
                      จัดการใบเบิกค่าใช้จ่าย
                    </h3>

                    <button type="button"
                      class="text-gray-400 bg-transparent hover:bg-gray-200 hover:text-gray-900 rounded-lg text-sm p-1.5 ml-auto inline-flex items-center dark:hover:bg-gray-600 dark:hover:text-white"
                      data-modal-hide="staticModal5">
                      <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                        <path fill-rule="evenodd"
                          d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z"
                          clip-rule="evenodd"></path>
                      </svg>
                    </button>
                  </div>
                  <!-- Modal body -->
                  <div class="p-6 space-y-6">
                    <table class="w-full text-sm text-center text-gray-500 dark:text-gray-400">
                      <thead class="text-xs text-white uppercase bg-green-400 dark:bg-gray-700 dark:text-gray-400">
                        <tr>
                          <th scope="col" class="px-2 py-2">
                            ชื่อผู้เบิก
                          </th>
                          <th scope="col" class="px-2 py-2">
                            วันที่เบิก
                          </th>
                          <th scope="col" class="px-2 py-2">
                            วัตถุประสงค์
                          </th>
                          <th scope="col" class="px-2 py-2">
                            ยอดสุทธิ
                          </th>
                          <th scope="col" class="px-4 py-2">
                            ฟังก์ชั่น
                          </th>
                        </tr>
                      </thead>
                      <tbody>
                        <tr
                          class="bg-white border-b dark:bg-gray-800 dark:border-gray-700 hover:bg-gray-50 dark:hover:bg-gray-600">
                          <td class="px-2 py-2">
                            อินทุอร หัวนิล
                          </td>
                          <td class="px-2 py-2">
                            25/03/2566
                          </td>
                          <td class="px-6 py-3">
                            ค่าใช้จ่ายภายในทริป อบต โพนงาม
                          </td>
                          <td class="px-6 py-3">
                            72,000.00
                          </td>
                          <td class="px-6 py-3">
                            <button type="button" class="w-full text-blue-600 bg-blue-200 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-blue-600 dark:hover:bg-blue-700 focus:outline-none dark:focus:ring-blue-800">ดูใบเบิกเงินสดย่อย</button>
                            <button type="button" class="w-full focus:outline-none text-yellow-600 bg-yellow-200 hover:bg-yellow-500 focus:ring-4 focus:ring-yellow-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:focus:ring-yellow-900">ดูใบอื่นๆ</button>
                            <button type="button" class="w-full focus:outline-none text-red-600 bg-red-200 hover:bg-red-800 focus:ring-4 focus:ring-red-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-red-600 dark:hover:bg-red-700 dark:focus:ring-red-900">ลบข้อมูล</button>
                          </td>
                        </tr>
                        <tr
                          class="bg-white border-b dark:bg-gray-800 dark:border-gray-700 hover:bg-gray-50 dark:hover:bg-gray-600">
                          <td class="px-2 py-2">
                            อินทุอร หัวนิล
                          </td>
                          <td class="px-2 py-2">
                            25/03/2566
                          </td>
                          <td class="px-6 py-3">
                            ค่าใช้จ่ายภายในทริป อบต โพนงาม
                          </td>
                          <td class="px-6 py-3">
                            72,000.00
                          </td>
                          <td class="px-6 py-3">
                            <button type="button" class="w-full text-blue-600 bg-blue-200 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-blue-600 dark:hover:bg-blue-700 focus:outline-none dark:focus:ring-blue-800">ดูใบเบิกเงินสดย่อย</button>
                            <button type="button" class="w-full focus:outline-none text-yellow-600 bg-yellow-200 hover:bg-yellow-500 focus:ring-4 focus:ring-yellow-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:focus:ring-yellow-900">ดูใบอื่นๆ</button>
                            <button type="button" class="w-full focus:outline-none text-red-600 bg-red-200 hover:bg-red-800 focus:ring-4 focus:ring-red-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-red-600 dark:hover:bg-red-700 dark:focus:ring-red-900">ลบข้อมูล</button>
                          </td>
                        </tr>
                      </tbody>
                    </table>
                  </div>
                  <!-- Modal footer -->
                  <div class="flex items-center p-6 space-x-2 border-t border-gray-200 rounded-b dark:border-gray-600">
                    <div class="relative ">
                      <button type="button" class="text-blue-600 bg-blue-200 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-blue-600 dark:hover:bg-blue-700 focus:outline-none dark:focus:ring-blue-800">สร้างใบเบิกค่าใช้จ่าย</button>
                      <button type="button"
                        class="focus:outline-none text-white bg-red-700 hover:bg-red-800 focus:ring-4 focus:ring-red-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-red-600 dark:hover:bg-red-700 dark:focus:ring-red-900">ปิด</button>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </li>
          <li>
            <button data-modal-target="staticModal6" data-modal-toggle="staticModal6"
              class="focus:outline-none text-blue-600 bg-blue-100 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 font-medium font-weight-bold rounded-lg text-sm text-white px-5 py-2.5 mr-2 mb-2 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800"
              type="button">
              จัดการใบเสนอราคา
            </button>

            <!-- Main modal -->
            <div id="staticModal6" data-modal-backdrop="static6" tabindex="-1" aria-hidden="true"
              class="fixed top-0 left-0 right-0 z-50 hidden w-full p-4 overflow-x-hidden overflow-y-auto md:inset-0 h-[calc(100%-1rem)] max-h-full">
              <div class="relative w-full max-w-2xl max-h-full">
                <!-- Modal content -->
                <div class="relative bg-white rounded-lg shadow-lg dark:bg-gray-700">
                  <!-- Modal header -->
                  <div class="flex items-start justify-between p-4 border-b rounded-t dark:border-gray-600">

                    <h3 class="text-xl font-semibold text-gray-900 dark:text-white">
                      รายการใบเสนอราคา
                    </h3>

                    <button type="button"
                      class="text-gray-400 bg-transparent hover:bg-gray-200 hover:text-gray-900 rounded-lg text-sm p-1.5 ml-auto inline-flex items-center dark:hover:bg-gray-600 dark:hover:text-white"
                      data-modal-hide="staticModal6">
                      <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                        <path fill-rule="evenodd"
                          d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z"
                          clip-rule="evenodd"></path>
                      </svg>
                    </button>
                  </div>
                  <!-- Modal body -->
                  <div class="p-6 space-y-6">
                    <table class="w-full text-sm text-center text-gray-500 dark:text-gray-400">
                      <thead class="text-xs text-white uppercase bg-green-400 dark:bg-gray-700 dark:text-gray-400">
                        <tr>
                          <th scope="col" class="px-2 py-2">
                            ชื่อลูกค้า
                          </th>
                          <th scope="col" class="px-2 py-2">
                            ชื่อผู้เสนอขาย
                          </th>
                          <th scope="col" class="px-2 py-2">
                            วันที่สร้างล่าสุด
                          </th>
                          <th scope="col" class="px-2 py-2">
                            ราคาเสนอ
                          </th>
                          <th scope="col" class="px-4 py-2">
                            ฟังก์ชั่น
                          </th>
                        </tr>
                      </thead>
                      <tbody>
                        <tr
                          class="bg-white border-b dark:bg-gray-800 dark:border-gray-700 hover:bg-gray-50 dark:hover:bg-gray-600">
                          <td class="px-2 py-2">
                            องค์การบริหารส่วนตำบลโพนงาม
                          </td>
                          <td class="px-2 py-2">
                            อินทุอร หัวนิล
                          </td>
                          <td class="px-6 py-3">
                            25/03/2566
                          </td>
                          <td class="px-6 py-3">
                            111,920.00
                          </td>
                          <td class="px-6 py-3">
                            <button type="button" class="w-full text-blue-600 bg-blue-200 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-blue-600 dark:hover:bg-blue-700 focus:outline-none dark:focus:ring-blue-800">ดูใบเสนอราคา</button>
                            <button type="button" class="w-full focus:outline-none text-yellow-600 bg-yellow-200 hover:bg-yellow-500 focus:ring-4 focus:ring-yellow-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:focus:ring-yellow-900">ดูใบอื่นๆ</button>
                            <button type="button" class="w-full focus:outline-none text-red-600 bg-red-200 hover:bg-red-800 focus:ring-4 focus:ring-red-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-red-600 dark:hover:bg-red-700 dark:focus:ring-red-900">ลบข้อมูล</button>
                          </td>
                        </tr>
                        <tr
                          class="bg-white border-b dark:bg-gray-800 dark:border-gray-700 hover:bg-gray-50 dark:hover:bg-gray-600">
                          <td class="px-2 py-2">
                            องค์การบริหารส่วนตำบลโพนงาม
                          </td>
                          <td class="px-2 py-2">
                            อินทุอร หัวนิล
                          </td>
                          <td class="px-6 py-3">
                            25/03/2566
                          </td>
                          <td class="px-6 py-3">
                            111,920.00
                          </td>
                          <td class="px-6 py-3">
                            <button type="button" class="w-full text-blue-600 bg-blue-200 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-blue-600 dark:hover:bg-blue-700 focus:outline-none dark:focus:ring-blue-800">ดูใบเสนอราคา</button>
                            <button type="button" class="w-full focus:outline-none text-yellow-600 bg-yellow-200 hover:bg-yellow-500 focus:ring-4 focus:ring-yellow-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:focus:ring-yellow-900">ดูใบอื่นๆ</button>
                            <button type="button" class="w-full focus:outline-none text-red-600 bg-red-200 hover:bg-red-800 focus:ring-4 focus:ring-red-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-red-600 dark:hover:bg-red-700 dark:focus:ring-red-900">ลบข้อมูล</button>
                          </td>
                        </tr>
                      </tbody>
                    </table>
                  </div>
                  <!-- Modal footer -->
                  <div class="flex items-center p-6 space-x-2 border-t border-gray-200 rounded-b dark:border-gray-600">
                    <div class="relative ">
                      <button type="button" class="text-blue-600 bg-blue-200 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-blue-600 dark:hover:bg-blue-700 focus:outline-none dark:focus:ring-blue-800">ดูใบเสนอราคา</button>
                      <button type="button"
                        class="focus:outline-none text-white bg-red-700 hover:bg-red-800 focus:ring-4 focus:ring-red-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-red-600 dark:hover:bg-red-700 dark:focus:ring-red-900">ปิด</button>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </li>
          <li>
            <button 
              class="focus:outline-none text-yellow-600 bg-yellow-100 hover:bg-yellow-800 focus:ring-4 focus:ring-yellow-300 font-medium font-weight-bold rounded-lg text-sm text-white px-5 py-2.5 mr-2 mb-2 dark:bg-yellow-600 dark:hover:bg-yellow-700 dark:focus:ring-yellow-800"
              type="button"
              onclick="location.href='addusertour'">
              จัดการข้อมูลลูกทัวร์
            </button>
        </li>
      </ul>
    </div>
  </div>
</footer>


<!-- second code --></template>