<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Phinma SIS - Down Payment</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body { background-color: #f1f5f9; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; }
        .sidebar-border { border-left: 4px solid #1a5e32; }
    </style>
</head>
<body class="p-4 md:p-10">

    <div class="max-w-5xl mx-auto bg-white shadow-md rounded-sm overflow-hidden">
        <div class="p-6 border-b border-gray-100">
            <h2 class="text-xl font-semibold text-gray-700 flex items-center gap-2">
                Down Payment <span class="text-sm">🔖</span>
            </h2>
            <div class="mt-4 space-y-1 text-sm text-blue-600 font-medium">
                <p>01-2324-043191</p>
                <p class="uppercase">Pangilinan, Kian James Aquino</p>
                <p>Bachelor of Science in Electrical Engineering</p>
                <p>COE - Bachelor of Science in Electrical Engineering - 23-24</p>
            </div>
        </div>

        <div class="flex border-b border-gray-100">
            <div class="flex-1 py-4 text-center border-t-4 border-gray-200">
                <span class="block text-xs font-bold text-gray-400 uppercase">Step 1</span>
                <span class="text-sm text-gray-500">Student Detail</span>
            </div>
            <div class="flex-1 py-4 text-center border-t-4 border-yellow-400">
                <span class="block text-xs font-bold text-green-600 uppercase">Step 2</span>
                <span class="text-sm font-semibold text-gray-700">Payment</span>
            </div>
            <div class="flex-1 py-4 text-center border-t-4 border-gray-200">
                <span class="block text-xs font-bold text-gray-400 uppercase">Step 3</span>
                <span class="text-sm text-gray-500">Down Payment Status</span>
            </div>
        </div>

        <div class="p-6">
            <section class="mb-8">
                <h3 class="sidebar-border pl-2 text-sm font-bold text-gray-700 uppercase mb-4">Fees Details</h3>
                <div class="overflow-hidden border border-gray-200 rounded">
                    <table class="w-full text-left text-sm">
                        <thead class="bg-gray-50 border-b">
                            <tr>
                                <th class="p-3 font-semibold text-gray-600">Payment Type</th>
                                <th class="p-3 font-semibold text-gray-600">Amount</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr class="border-b">
                                <td class="p-3 uppercase">Down Payment Amount</td>
                                <td class="p-3">0.00</td>
                            </tr>
                            <tr class="bg-blue-50 font-bold">
                                <td class="p-3">Total Amount</td>
                                <td class="p-3">0.00</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
            </section>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-8">
                <div class="border rounded p-4 bg-white shadow-sm">
                    <h3 class="sidebar-border pl-2 text-sm font-bold text-gray-700 uppercase mb-3">Pay In Cash</h3>
                    <p class="text-sm font-medium">Amount : <span class="text-blue-600 font-bold">0.00</span></p>
                </div>
                <div class="border rounded p-4 bg-white shadow-sm">
                    <h3 class="sidebar-border pl-2 text-sm font-bold text-gray-700 uppercase mb-3">Pay Online</h3>
                    <p class="text-sm font-medium mb-4">Amount : <span class="text-blue-600 font-bold">0.00</span></p>
                    <button class="border border-blue-400 text-blue-500 px-6 py-1.5 rounded text-sm hover:bg-blue-50 transition">Pay Online</button>
                </div>
            </div>

            <div class="mb-10">
                <p class="text-green-700 font-semibold italic text-lg">Dear Candidate, Your payment is verified.</p>
            </div>

            <section>
                <h3 class="sidebar-border pl-2 text-sm font-bold text-gray-700 uppercase mb-4">Previous Receipts Information</h3>
                <div class="overflow-x-auto">
                    <table class="w-full text-xs sm:text-sm border text-gray-600 border-collapse">
                        <thead class="bg-gray-50">
                            <tr>
                                <th class="p-2 border">Print</th>
                                <th class="p-2 border">Registration No</th>
                                <th class="p-2 border">Receipt Type</th>
                                <th class="p-2 border">Receipt No</th>
                                <th class="p-2 border">Date</th>
                                <th class="p-2 border">Semester</th>
                                <th class="p-2 border">Payment Status</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr class="text-center">
                                <td class="p-2 border">🖨️</td>
                                <td class="p-2 border">01-2324-043191</td>
                                <td class="p-2 border">DP</td>
                                <td class="p-2 border">01-238334</td>
                                <td class="p-2 border">05/12/2026</td>
                                <td class="p-2 border">Y2 Summer</td>
                                <td class="p-2 border font-bold text-green-600">COMPLETE</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
            </section>
        </div>
    </div>

    <footer class="mt-10 text-center text-xs text-gray-400">
        © 2026 MasterSoft ERP Solution Pvt Ltd. All Rights Reserved.
    </footer>

</body>
</html>
