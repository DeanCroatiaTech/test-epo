   Serenity Reports                       jQuery.fn.dataTable.ext.type.order\['time-elapsed-dhms-pre'\] = function(data) { var matches = data.match(/^(\\d+(?:\\.\\d+)?)\\s\*(\[a-z\]+)/i); var multipliers = { ms: 1, s: 1000, m: 60000, h: 3600000, d: 86400000 }; if (matches) { var multiplier = multipliers\[matches\[2\].toLowerCase()\]; return parseFloat(matches\[1\]) \* multiplier; } else { return -1; }; };     // Register the plugin to all charts: Chart.register(ChartDataLabels);    jQuery.fn.dataTable.ext.type.order\['time-elapsed-dhms-pre'\] = function(data) { var matches = data.match(/^(\\d+(?:\\.\\d+)?)\\s\*(\[a-z\]+)/i); var multipliers = { ms: 1, s: 1000, m: 60000, h: 3600000, d: 86400000 }; if (matches) { var multiplier = multipliers\[matches\[2\].toLowerCase()\]; return parseFloat(matches\[1\]) \* multiplier; } else { return -1; }; }; $(document).ready(function () { $('.scenario-result-table').DataTable({ "order": \[\[0, "asc",\], \[3, "asc",\]\], "pageLength": 10, "language": { searchPlaceholder: "Filter", search: "" }, columnDefs: \[ {type: 'time-elapsed-dhms', targets: 4} \] }); $('.manual-scenario-result-table').DataTable({ "order": \[\[0, "asc",\], \[3, "asc",\]\], "pageLength": 10, "language": { searchPlaceholder: "Filter", search: "" }, }); // Results table $('#test-results-table').DataTable({ "order": \[\[0, "asc",\], \[3, "asc",\]\], "pageLength": 10, "lengthMenu": \[\[10, 25, 50, 100, 200, -1\], \[10, 25, 50, 100, 200, "All"\]\] }); $('#evidence-table').DataTable({ searching: false, paging: false, info: false }); $(".feature-coverage-table").DataTable({ searching: true, paging: false, info: false }); $(".feature-coverage-table-with-pagination").DataTable({ searching: true, order: \[\[0, "asc",\]\], pageLength: 10, language: { searchPlaceholder: "Filter", search: "" } }); });

[![](images/serenity-logo.png)](index.html)

Serenity BDD Report

[Home](index.html)

*   [Overall Test Results](#)
*   [Requirements](capabilities.html)

[](build-info.html)Report generated 14-03-2024 07:28:46  

Test Results: All Tests
-----------------------

8 tests

*   [Summary](#summary)
*   [Test Results](#tests)

#### Overview

#### Test Outcomes

#### Test Performance

### Key Statistics

Number of Scenarios

8

Number of Test Cases

8

Tests Started

Mar 14, 2024 07:25:40

Tests Finished

Mar 14, 2024 07:28:44

Total Duration

3m 3s

Fastest Test

22s

Slowest Test

1m 34s

Average Execution Time

55s

Total Execution Time

7m 25s

### Tags

[SIT1 Internalportal   8](a34d8215f3b549bb465d0ee2ce9acbd0a604f9d4a4f51485271125aaa0dc7078.html)

##### Story

[Internal Portal/Organisations   3](8a37b884ff82ea1571361bfbb74b994c23f6aa15051d687bb7db361410245c25.html) [Internal Portal/System Maintenance   2](3e21a2a1223c74c6ac71a1d1af64d61e9020aa959fd631f3ed95ce2fd7084d03.html) [Internal Portal/Internal Portal   3](4e96953e7381db0656d87e398d6b28cc14ba1bc9f3773a58253e4bab6244b839.html)

### Automated Tests

Feature

Scenario

Steps

Started

Total Duration

Result

[Organisations](8a37b884ff82ea1571361bfbb74b994c23f6aa15051d687bb7db361410245c25.html)

[008 Adding organization into EPO portal](a019752d57c5e4248769837144a7b81673cd77b06d40755c8a95474384d1a7dc.html)

5

07:25:40

1m

[](##beforetable)SUCCESS

[System maintenance](3e21a2a1223c74c6ac71a1d1af64d61e9020aa959fd631f3ed95ce2fd7084d03.html)

[Add a system message: schedule date=today, exiry date=2 days later](58af2d6cf8772519d3841c2937584908fc8f9f5c37cc24965be4deed0e3e7275.html)

5

07:25:40

1m 8s

[](##beforetable)SUCCESS

[Internal portal](4e96953e7381db0656d87e398d6b28cc14ba1bc9f3773a58253e4bab6244b839.html)

[001 Login to internal portal as administrator](1bf002b21d8be6a22bfcf011dcd3d77edbd0df22e9598b634d54d24c9c5e1afc.html)

6

07:25:40

50s 445ms

[](##beforetable)SUCCESS

[Internal portal](4e96953e7381db0656d87e398d6b28cc14ba1bc9f3773a58253e4bab6244b839.html)

[004 User rights and permissions - Admin](7dfb7fcee49b8ffceaf9469f464dfde3ef8e034958c6d2286e6de5a42de6d134.html)

14

07:26:31

1m 34s

[](##beforetable)SUCCESS

[Organisations](8a37b884ff82ea1571361bfbb74b994c23f6aa15051d687bb7db361410245c25.html)

[009 De-activation of an organization](25112df2f2f2773b88d00e5db749c37be16cfdb409b5961dc225c9b959a5002a.html)

4

07:26:41

56s 423ms

[](##beforetable)SUCCESS

[System maintenance](3e21a2a1223c74c6ac71a1d1af64d61e9020aa959fd631f3ed95ce2fd7084d03.html)

[Add a system message: schedule date=today, exiry date=empty](5091b70f5d8b9a26cd500b2f74f4b8519afff8c934cf5eb17189369ef1787063.html)

5

07:26:48

22s 471ms

[](##beforetable)SUCCESS

[Organisations](8a37b884ff82ea1571361bfbb74b994c23f6aa15051d687bb7db361410245c25.html)

[010 Edit an organization](a8c4bd51f5b86202f21a055347b609a676fbc069f48789124d5260b60cb86928.html)

4

07:27:37

54s 957ms

[](##beforetable)SUCCESS

[Internal portal](4e96953e7381db0656d87e398d6b28cc14ba1bc9f3773a58253e4bab6244b839.html)

[005 Import users](fb8c147fe073a3d67f01bc8716a9f20acb1f12bd32d3dde1a7f28cf21c7e8bf4.html)

12

07:28:05

38s 912ms

[](##beforetable)SUCCESS

### Manual Tests

No manual tests were recorded

Serenity BDD version 3.4.3

// The results pie chart const outcomeChartCtx = document.getElementById('resultChart'); // Options define for display value on top of bars const outcomeDetailsReports = \[ { title: 'Passing Test Cases', link: "01f5288b80adbd3af52a8ed68a4a616d3164f750229f80da1ef344382d948835.html" }, { title: 'Pending Test Cases', link: "bde4fca42ca8baa0fe2eac76a241c84327dfe4ca903a1daa7cae83a1035d4745.html" }, { title: 'Ignored Test Cases', link: "c1b352893c3d69e59317fd825f20a75f987a859afe98fb4434f47dce70c48fd4.html" }, { title: 'Skipped Test Cases', link: "7409dbb9985b960343780b303d8028480bd55e9aebd855c90eff0a000e21ccc8.html" }, { title: 'Aborted Test Cases', link: "91152e032be7fe762aa6823d6424278e2c72efeb7622a5e63c7bf5980b4fd8a0.html"}, { title: 'Failed Test Cases', link: "da5b0c51b332adf0ef993a9f086d6a1b51a3d800248ec6ae281212092f35bd37.html" }, { title: 'Broken Test Cases', link: "c8a926210aeff57f8aa7ea799262d4b730915a909cd5ecd6a705b1fa13bc7aa8.html" }, { title: 'Compromised Test Cases', link: "02dd8f8ada4c10b8ebb5c1f309605a6f7c147adc21bcf5c55829855ba045ff03.html" }, \] const outcomeData = { labels: \['Passing Test Cases', 'Pending Test Cases', 'Ignored Test Cases', 'Skipped Test Cases', 'Aborted Test Cases', 'Failed Test Cases', 'Broken Test Cases', 'Compromised Test Cases','Undefined Test Cases'\], datasets: \[{ label: 'Test Results', fill: false, data: \[8,0,0,0,0,0,0,0\], backgroundColor: \['rgba(153,204,51,0.5)','rgba(165, 199, 238, 0.5)','rgba(168, 168, 168, 0.5)','rgba(238, 224, 152, 0.75)','rgba(255, 153, 102, 0.5)','rgba(255, 22, 49, 0.5)','rgba(255, 97, 8, 0.5)','rgba(255, 104, 255, 0.5)','rgba(83, 50, 168, 0.5)'\], borderColor: \['rgba(153,204,51,1)','rgba(165, 199, 238, 1)','rgba(168, 168, 168, 1)','rgba(238, 224, 152, 1)','rgba(255, 153, 102, 1)','rgba(255, 22, 49, 1)','rgba(255, 97, 8, 1)','rgba(255, 104, 255, 1)','rgba(83, 50, 168, 1)'\], borderWidth: 1, }\] } const outcomeOptions = { responsive: true, plugins: { legend: { display: true, position: 'bottom' }, // Change options for ALL labels of THIS CHART datalabels: { color: '#444444', 'font.weight': 'bold', formatter: (value, ctx) => { let sum = 0; let dataArr = ctx.chart.data.datasets\[0\].data; dataArr.map(data => { sum += data; }); let percentage = (value \* 100 / sum).toFixed(0) + "%"; if (percentage === '0%' || percentage === 'NaN%') { return ''; } else { return percentage; } }, }, } } const outcomeChart = new Chart(outcomeChartCtx, { type: 'doughnut', data: outcomeData, options: outcomeOptions, plugins: \[ { id: 'text', beforeDraw: function (chart, a, b) { var width = chart.width, height = chart.height, ctx = chart.ctx; ctx.restore(); var fontSize = (height / 200).toFixed(1); ctx.font = fontSize + "em sans-serif"; ctx.textBaseline = "middle"; var text = "100%" textX = 10 + Math.round((width - ctx.measureText(text).width) / 2); textY = (height / 2) - 40; ctx.fillText(text, textX, textY); ctx.save(); } }\] }); function clickHandler(click) { const points = outcomeChart.getElementsAtEventForMode(click, 'nearest', {intersect: true}, true); if (points.length) { const firstPoint = points\[0\]; window.open(outcomeDetailsReports\[firstPoint.index\].link, "\_self") } } outcomeChartCtx.onclick = clickHandler; // The Severity bar chart const severityChartCtx = document.getElementById('severityChart'); // Options define for display value on top of bars const severityDetailsReports = \[ { title: 'Passing Scenarios', link: "01f5288b80adbd3af52a8ed68a4a616d3164f750229f80da1ef344382d948835.html" }, { title: 'Pending Scenarios', link: "bde4fca42ca8baa0fe2eac76a241c84327dfe4ca903a1daa7cae83a1035d4745.html" }, { title: 'Ignored Scenarios', link: "c1b352893c3d69e59317fd825f20a75f987a859afe98fb4434f47dce70c48fd4.html" }, { title: 'Skipped Scenarios', link: "7409dbb9985b960343780b303d8028480bd55e9aebd855c90eff0a000e21ccc8.html" }, { title: 'Aborted Scenarios', link: "91152e032be7fe762aa6823d6424278e2c72efeb7622a5e63c7bf5980b4fd8a0.html"}, { title: 'Failed Scenarios', link: "da5b0c51b332adf0ef993a9f086d6a1b51a3d800248ec6ae281212092f35bd37.html" }, { title: 'Broken Scenarios', link: "c8a926210aeff57f8aa7ea799262d4b730915a909cd5ecd6a705b1fa13bc7aa8.html" }, { title: 'Compromised Scenarios', link: "02dd8f8ada4c10b8ebb5c1f309605a6f7c147adc21bcf5c55829855ba045ff03.html" }, \] const severityData = { labels: \['Passing', 'Pending', 'Ignored', 'Skipped', 'Aborted', 'Failed', 'Broken', 'Compromised'\], datasets: \[ { label: 'Automated', data: \[8,0,0,0,0,0,0,0\], backgroundColor: \['rgba(153,204,51,0.5)','rgba(165, 199, 238, 0.5)','rgba(168, 168, 168, 0.5)','rgba(238, 224, 152, 0.75)','rgba(255, 153, 102, 0.5)','rgba(255, 22, 49, 0.5)','rgba(255, 97, 8, 0.5)','rgba(255, 104, 255, 0.5)','rgba(83, 50, 168, 0.5)'\], borderColor: \['rgba(153,204,51,1)','rgba(165, 199, 238, 1)','rgba(168, 168, 168, 1)','rgba(238, 224, 152, 1)','rgba(255, 153, 102, 1)','rgba(255, 22, 49, 1)','rgba(255, 97, 8, 1)','rgba(255, 104, 255, 1)','rgba(83, 50, 168, 1)'\], borderWidth: 1 }, { label: 'Manual', data: \[0,0,0,0,0,0,0,0\], backgroundColor: \['rgba(153,204,51,0.25)','rgba(165, 199, 238, 0.25)','rgba(168, 168, 168, 0.25)','rgba(238, 224, 152, 0.375)','rgba(255, 153, 102, 0.25)','rgba(255, 22, 49, 0.25)','rgba(255, 97, 8, 0.25)','rgba(255, 104, 255, 0.25)','rgba(83, 50, 168, 0.25)'\], borderColor: \['rgba(153,204,51,1)','rgba(165, 199, 238, 1)','rgba(168, 168, 168, 1)','rgba(238, 224, 152, 1)','rgba(255, 153, 102, 1)','rgba(255, 22, 49, 1)','rgba(255, 97, 8, 1)','rgba(255, 104, 255, 1)','rgba(83, 50, 168, 1)'\], borderWidth: 1 }, \] } const severityOptions = { responsive: true, skipNull: true, scales: { x: { stacked: true, }, y: { stacked: true, } }, plugins: { // Change options for ALL labels of THIS CHART datalabels: { color: '#444444', 'font.weight': 'bold', formatter: (value, ctx) => { if (value === 0) { return ''; } else { return value; } }, } } } const severityChart = new Chart(severityChartCtx, { type: 'bar', data: severityData, options: severityOptions }); function clickHandler(click) { const points = severityChart.getElementsAtEventForMode(click, 'nearest', {intersect: true}, true); if (points.length) { const firstPoint = points\[0\]; window.open(severityDetailsReports\[firstPoint.index\].link, "\_self") } } severityChartCtx.onclick = clickHandler; // Options define for display value on top of bars const durationDetailsReports = \[ {title: "Under 1 second", link: "2a5b6a7be0f08df02d8ab0b4d4c68648c2695c6c7ef0658c71de4d42b1415b18.html"}, {title: "1 to 10 seconds", link: "6c5512236937b92cd7a296b24edb966c2bd94be46b8910f8b129a42d6150eb25.html"}, {title: "10 to 30 seconds", link: "34658a1663fcf042bd7acb3325affbe4e647c8acd84d0228be2f52e1381e61b9.html"}, {title: "30 to 60 seconds", link: "5698da923f295f46ce5ab64ced2311fc60caa4e36b32112606d3adcfdce3f60b.html"}, {title: "1 to 2 minutes", link: "c68fd6639ab29c4b0ac02a78bc39f4e22557bcaa40ef14c903ac0e584626edfe.html"}, {title: "2 to 5 minutes", link: "3ce388ea8511800032930896a3e5ba2c4f80e46f1a10b143b67009baf212c6a0.html"}, {title: "5 to 10 minutes", link: "376e1536bb68812a880e84ca7a0c6d104d541788793f22a36b4462a6a9aaa344.html"}, {title: "10 minutes or over", link: "24bba6f5cf4f06c7d46bf8990b86c4fbc1ce4ce201644ddf42661c84031e1c90.html"}, \] // The Severity bar chart const durationChartCtx = document.getElementById('durationChart'); // Options define for display value on top of bars const durationData = { labels: \['Under 1 second','1 to 10 seconds','10 to 30 seconds','30 to 60 seconds','1 to 2 minutes','2 to 5 minutes','5 to 10 minutes','10 minutes or over'\], datasets: \[{ label: 'Number of tests per duration', fill: false, data: \['0','0','1','4','3','0','0','0'\], backgroundColor: 'rgba(83, 146, 255,0.5)', borderColor: 'rgba(83, 146, 255, 1)', }\] } const durationOptions = { responsive: true, plugins: { // Change options for ALL labels of THIS CHART datalabels: { color: '#444444', 'font.weight': 'bold', formatter: (value, ctx) => { if (value > 0) { return value; } else { return ''; } }, }, tooltip: { enabled: true, usePointStyle: true, callbacks: { label: (data) => { return data.parsed.y + ' tests' } }, }, }, } const durationChart = new Chart(durationChartCtx, { type: 'bar', data: durationData, options: durationOptions }); function durationClickHandler(click) { const points = durationChart.getElementsAtEventForMode(click, 'nearest', {intersect: true}, true); if (points.length) { const firstPoint = points\[0\]; window.open(durationDetailsReports\[firstPoint.index\].link, "\_self") } } durationChartCtx.onclick = durationClickHandler;
