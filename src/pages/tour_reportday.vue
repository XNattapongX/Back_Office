<template>
  
<div class="text-sm font-medium text-center text-gray-500 border-b border-gray-200 dark:text-gray-400 dark:border-gray-700">
    <ul class="flex flex-wrap -mb-px">
        <li class="mr-2">
            <a href="tour_reportday" class="inline-block p-4 text-blue-600 border-b-2 border-blue-600 rounded-t-lg active dark:text-blue-500 dark:border-blue-500" aria-current="page">วัน</a>
        </li>
        <li class="mr-2">
            <a href="tour_reportmonth" class="inline-block p-4 border-b-2 border-transparent rounded-t-lg hover:text-gray-600 hover:border-gray-300 dark:hover:text-gray-300">เดือน</a>
        </li>
        <li class="mr-2">
            <a href="tour_reportyear" class="inline-block p-4 border-b-2 border-transparent rounded-t-lg hover:text-gray-600 hover:border-gray-300 dark:hover:text-gray-300">ปี</a>
        </li>
        <li class="mr-2">
            <a href="tour_reportmonth2" class="inline-block p-4 border-b-2 border-transparent rounded-t-lg hover:text-gray-600 hover:border-gray-300 dark:hover:text-gray-300">รายเดือน(แบบละเอียด)</a>
        </li>
    </ul>
</div>
<br>
เลือกวัน/เดือน/ปี
<div class="relative max-w-sm">
  <input type="date" id="start" name="trip-start" value="" min="2023-01-01" max="2023-12-31" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500">
</div>
<p class="text-right text-gray-500 dark:text-gray-400">
    รายรับ
    <span class="bg-green-100 text-green-800 text-xs font-medium mr-2 px-2.5 py-0.5 rounded dark:bg-gray-700 dark:text-green-400 border border-green-400">541521</span>
    |
    รายจ่าย
    <span class="bg-red-100 text-red-800 text-xs font-medium mr-2 px-2.5 py-0.5 rounded dark:bg-gray-700 dark:text-red-400 border border-red-400">370872</span>
    &nbsp;&nbsp;&nbsp;&nbsp;
    กำไร / ขาดทุน
    <span class="bg-green-50 text-green-800 text-xs font-medium mr-2 px-2.5 py-0.5 rounded dark:bg-gray-700 dark:text-green-400 border border-green-200">170649</span>
</p>


<br>

<div class="relative overflow-x-auto">
    <table class="w-full text-sm text-left text-gray-500 dark:text-gray-400">
        <thead class="text-xs text-white uppercase bg-blue-600 dark:bg-gray-700 dark:text-white-400">
            <tr>
                <th scope="col" class="px-6 py-3 rounded-l-lg">
                    ลำดับ
                </th>
                <th scope="col" class="px-6 py-3">
                    รายการ
                </th>
                <th scope="col" class="px-6 py-3">
                    รายรับ(บาท)
                </th>
                <th scope="col" class="px-6 py-3">
                    รายจ่าย(บาท)
                </th>
                <th scope="col" class="px-6 py-3 rounded-r-lg">
                    หมายเหตุ
                </th>
            </tr>
        </thead>
        <tbody>
            <tr class="bg-white dark:bg-gray-800">
                <th scope="row" class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                    1
                </th>
                <td class="px-6 py-4">
                    เที่ยวเกาะ เลาะรัก
                </td>
                <td class="px-6 py-4">
                    <span class="bg-green-100 text-green-800 text-xs font-medium mr-2 px-2.5 py-0.5 rounded dark:bg-gray-700 dark:text-green-400 border border-green-400">59920</span>
                </td>
                <td class="px-6 py-4">
                    -
                </td>
                <td class="px-6 py-4">
                   
                </td>
            </tr>
            <tr class="bg-white dark:bg-gray-800">
                <th scope="row" class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                    2
                </th>
                <td class="px-6 py-4">
                    เที่ยวเกาะ เลาะรัก
                </td>
                <td class="px-6 py-4">
                    <span class="bg-green-100 text-green-800 text-xs font-medium mr-2 px-2.5 py-0.5 rounded dark:bg-gray-700 dark:text-green-400 border border-green-400">59920</span>
                </td>
                <td class="px-6 py-4">
                    -
                </td>
                <td class="px-6 py-4">
                   
                </td>
            </tr>
            <tr class="bg-white dark:bg-gray-800">
                <th scope="row" class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                    3
                </th>
                <td class="px-6 py-4">
                    ซื้อข้าวเที่ยง
                </td>
                <td class="px-6 py-4">
                    -
                </td>
                <td class="px-6 py-4">
                    <span class="bg-red-100 text-red-800 text-xs font-medium mr-2 px-2.5 py-0.5 rounded dark:bg-gray-700 dark:text-red-400 border border-red-400">750</span>
                </td>
                <td class="px-6 py-4">
                   
                </td>
            </tr>
            <tr class="bg-white dark:bg-gray-800">
                <th scope="row" class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                    4
                </th>
                <td class="px-6 py-4">
                    เที่ยวเกาะ เลาะรัก
                </td>
                <td class="px-6 py-4">
                    <span class="bg-green-100 text-green-800 text-xs font-medium mr-2 px-2.5 py-0.5 rounded dark:bg-gray-700 dark:text-green-400 border border-green-400">59920</span>
                </td>
                <td class="px-6 py-4">
                    -
                </td>
                <td class="px-6 py-4">
                   
                </td>
            </tr>
            <tr class="bg-white dark:bg-gray-800">
                <th scope="row" class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                    5
                </th>
                <td class="px-6 py-4">
                    ค่าใช้จ่ายภายในทริป อบต โพนงาม	
                </td>
                <td class="px-6 py-4">
                    -
                </td>
                <td class="px-6 py-4">
                    <span class="bg-red-100 text-red-800 text-xs font-medium mr-2 px-2.5 py-0.5 rounded dark:bg-gray-700 dark:text-red-400 border border-red-400">72000</span>
                </td>
                <td class="px-6 py-4">
                   
                </td>
            </tr>
            <tr class="bg-white dark:bg-gray-800">
                <th scope="row" class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                    6
                </th>
                <td class="px-6 py-4">
                    ค่าใช้จ่ายภายในทริป อบต โพนงาม	
                </td>
                <td class="px-6 py-4">
                    -
                </td>
                <td class="px-6 py-4">
                    <span class="bg-red-100 text-red-800 text-xs font-medium mr-2 px-2.5 py-0.5 rounded dark:bg-gray-700 dark:text-red-400 border border-red-400">72000</span>
                </td>
                <td class="px-6 py-4">
                   
                </td>
            </tr>
            <tr class="bg-white dark:bg-gray-800">
                <th scope="row" class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                    7
                </th>
                <td class="px-6 py-4">
                    ค่าใช้จ่ายภายในทริป อบต โพนงาม	
                </td>
                <td class="px-6 py-4">
                    -
                </td>
                <td class="px-6 py-4">
                    <span class="bg-red-100 text-red-800 text-xs font-medium mr-2 px-2.5 py-0.5 rounded dark:bg-gray-700 dark:text-red-400 border border-red-400">72000</span>
                </td>
                <td class="px-6 py-4">
                   
                </td>
            </tr>
            <tr class="bg-white dark:bg-gray-800">
                <th scope="row" class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                    8
                </th>
                <td class="px-6 py-4">
                    องค์การบริหารส่วนตำบลโพนงาม	
                </td>
                <td class="px-6 py-4">
                    <span class="bg-green-100 text-green-800 text-xs font-medium mr-2 px-2.5 py-0.5 rounded dark:bg-gray-700 dark:text-green-400 border border-green-400">111920</span>
                </td>
                <td class="px-6 py-4">
                    -
                </td>
                <td class="px-6 py-4">
                   
                </td>
            </tr>
            <tr class="bg-white dark:bg-gray-800">
                <th scope="row" class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                    9
                </th>
                <td class="px-6 py-4">
                    ค่าใช้จ่ายภายในทริป อบต โพนงาม	
                </td>
                <td class="px-6 py-4">
                    -
                </td>
                <td class="px-6 py-4">
                    <span class="bg-red-100 text-red-800 text-xs font-medium mr-2 px-2.5 py-0.5 rounded dark:bg-gray-700 dark:text-red-400 border border-red-400">72000</span>
                </td>
                <td class="px-6 py-4">
                   
                </td>
            </tr>
            <tr class="bg-white dark:bg-gray-800">
                <th scope="row" class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                    10
                </th>
                <td class="px-6 py-4">
                    ค่าใช้จ่ายภายในทริป อบต โพนงาม	
                </td>
                <td class="px-6 py-4">
                    -
                </td>
                <td class="px-6 py-4">
                    <span class="bg-red-100 text-red-800 text-xs font-medium mr-2 px-2.5 py-0.5 rounded dark:bg-gray-700 dark:text-red-400 border border-red-400">72000</span>
                </td>
                <td class="px-6 py-4">
                   
                </td>
            </tr>
            <tr class="bg-white dark:bg-gray-800">
                <th scope="row" class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                    11
                </th>
                <td class="px-6 py-4">
                    องค์การบริหารส่วนตำบลโพนงาม	
                </td>
                <td class="px-6 py-4">
                    <span class="bg-green-100 text-green-800 text-xs font-medium mr-2 px-2.5 py-0.5 rounded dark:bg-gray-700 dark:text-green-400 border border-green-400">111920</span>
                </td>
                <td class="px-6 py-4">
                    -
                </td>
                <td class="px-6 py-4">
                   
                </td>
            </tr>
            <tr class="bg-white dark:bg-gray-800">
                <th scope="row" class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                    12
                </th>
                <td class="px-6 py-4">
                    องค์การบริหารส่วนตำบลโพนงาม	
                </td>
                <td class="px-6 py-4">
                    <span class="bg-green-100 text-green-800 text-xs font-medium mr-2 px-2.5 py-0.5 rounded dark:bg-gray-700 dark:text-green-400 border border-green-400">111920</span>
                </td>
                <td class="px-6 py-4">
                    -
                </td>
                <td class="px-6 py-4">
                   
                </td>
            </tr>
        </tbody>
    </table>
</div>

</template>
