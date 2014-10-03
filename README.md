<html xmlns="http://www.w3.org/1999/xhtml">
<head>
    <title>Apache HTTP Server FastPack</title>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8"/>
    <meta http-equiv="X-UA-Compatible" content="IE=EmulateIE8" />
    <meta content="Scroll Wiki Publisher" name="generator"/>
    <link type="text/css" rel="stylesheet" href="css/blueprint/liquid.css" media="screen, projection"/>
    <link type="text/css" rel="stylesheet" href="css/blueprint/print.css" media="print"/>
    <link type="text/css" rel="stylesheet" href="css/content-style.css" media="screen, projection, print"/>
    <link type="text/css" rel="stylesheet" href="css/screen.css" media="screen, projection"/>
    <link type="text/css" rel="stylesheet" href="css/print.css" media="print"/>
</head>
<body>
                <h1>Apache HTTP Server FastPack</h1>
    <div class="section-2"  id="63766552_ApacheHTTPServerFastPack-Overview"  >
        <h2>Overview</h2>
    <p>
            <img src="images_community/download/attachments/25789254/logo_apachehttpd.png" alt="images_community/download/attachments/25789254/logo_apachehttpd.png" class="confluence-embedded-image image-left" />
        The dynaTrace FastPack for Apache HTTP Server enables easy out-of-the-box monitoring of Apache HTTP Server performance data. The FastPack consists of a custom Monitor, Sample Profile and Dashboards.    </p>
    </div>
    <div class="section-2"  id="63766552_ApacheHTTPServerFastPack-FastPackDetails"  >
        <h2>Fast Pack Details</h2>
    <div class="tablewrap">
        <table>
<thead class=" "></thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
Name    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<strong class=" ">Apache HTTP Server Monitoring FastPack</strong>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Version    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
1.0.7    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
dynaTrace Version    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
4+, 5.5    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Author    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="http://www.mcg-software.dk/">MCG Systems</a> - Rasmus Toelhoej    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
License    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="attachments_5275722_2_dynaTraceBSD.txt">dynaTrace BSD</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Support    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="https://community/display/DL/Support+Levels#SupportLevels-Community">Not Supported </a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
FastPack Contents    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Fastpack Download (<a href="attachments_76775473_1_dynaTrace_Apache_FastPack_1.0.7.dtp">for 4+</a>, <a href="attachments_137756839_1_dynaTrace_Apache_FastPack_dt55.dtp">for 5.5</a>) contains:    </p>
<ul class=" "><li class=" ">    <p>
Apache Server Performance Dashboard    </p>
</li><li class=" ">    <p>
Apache Anomalies Dashboard    </p>
</li><li class=" ">    <p>
Sample System Profile    </p>
</li><li class=" ">    <p>
Apache Monitor Plugin (<a href="https://community/display/DL/Apache+Monitor+Plugin">Plugin Page</a>)    </p>
</li></ul>            </td>
        </tr>
</tbody>        </table>
            </div>
    </div>
    <div class="section-2"  id="63766552_ApacheHTTPServerFastPack-ApacheServerPerformanceDashboard"  >
        <h2>Apache Server Performance Dashboard</h2>
    <p>
            <img src="images_community/download/attachments/63766552/apache_server_performance_dashboard.png" alt="images_community/download/attachments/63766552/apache_server_performance_dashboard.png" class="" />
            </p>
    <p>
The Apache Server Performance Dashboard enables you to easily monitor one or multiple Apache Monitors. It shows you    </p>
<ul class=" "><li class=" ">    <p>
busy workers    </p>
</li><li class=" ">    <p>
bytes per second    </p>
</li><li class=" ">    <p>
requests per second    </p>
</li><li class=" ">    <p>
a scoreboard    </p>
</li><li class=" ">    <p>
a performance overview on workers utilization.    </p>
</li></ul>    </div>
    <div class="section-2"  id="63766552_ApacheHTTPServerFastPack-ApacheAnomaliesDashboard"  >
        <h2>Apache Anomalies Dashboard</h2>
    <p>
            <img src="images_community/download/attachments/63766552/apache_anormalies_dashboard.PNG" alt="images_community/download/attachments/63766552/apache_anormalies_dashboard.PNG" class="" />
            </p>
    <p>
The Apache Anormalies Dashboard enables you to easily monitor average worker utilization as well as incidents. It shows you    </p>
<ul class=" "><li class=" ">    <p>
Whether incidents have occurred on Apache    </p>
</li><li class=" ">    <p>
The average worker utilization    </p>
</li></ul>    </div>
    <div class="section-2"  id="63766552_ApacheHTTPServerFastPack-ApacheHTTPServerMonitor"  >
        <h2>Apache HTTP Server Monitor</h2>
    <p>
The Monitor uses the Apache Server Status page provided by <a href="http://httpd.apache.org/docs/2.0/mod/mod_status.html">mod_status</a> to gather its metrics. It monitors:    </p>
<ul class=" "><li class=" ">    <p>
Total Accesses    </p>
</li><li class=" ">    <p>
Total kBytes    </p>
</li><li class=" ">    <p>
CPULoad    </p>
</li><li class=" ">    <p>
Uptime    </p>
</li><li class=" ">    <p>
ReqPerSec    </p>
</li><li class=" ">    <p>
BytesPerSec    </p>
</li><li class=" ">    <p>
BytesPerReq    </p>
</li><li class=" ">    <p>
BusyWorkers    </p>
</li><li class=" ">    <p>
IdleWorkers    </p>
</li><li class=" ">    <p>
Worker Utilization    </p>
</li><li class=" ">    <p>
Scoreboard Statuses    </p>
</li></ul>    <p>
For more information please see the <a href="https://community/display/DL/Apache+Monitor+Plugin">Apache Monitor Plugin</a> page.    </p>
    </div>
    <div class="section-2"  id="63766552_ApacheHTTPServerFastPack-FastPackInformation"  >
        <h2>FastPack Information</h2>
    <p>
The Apache HTTP Server FastPack contains everything to get started with Apache HTTP Server monitoring.    </p>
<ul class=" "><li class=" ">    <p>
A system profile with a pre-configured monitor for monitoring Apache server    </p>
</li><li class=" ">    <p>
A Apache Server Performance Dashboard for performance monitoring    </p>
</li><li class=" ">    <p>
A Apache Anomalies Dashboard for monitoring average utilization and incidents    </p>
</li></ul>    </div>
    <div class="section-2"  id="63766552_ApacheHTTPServerFastPack-Installation"  >
        <h2>Installation</h2>
    <p>
Just download and import the FastPack on your dynaTrace Server (see <a href="https://community/display/DOCDT40/Plugin+Management">Plugin Management</a>)    </p>
    </div>
            </div>
        </div>
        <div class="footer">
        </div>
    </div>
</body>
</html>
