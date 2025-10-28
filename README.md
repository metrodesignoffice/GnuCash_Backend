<!DOCTYPE html>
<html>
<head>
	<meta http-equiv="content-type" content="text/html; charset=utf-8"/>
	<title></title>
	<meta name="generator" content="LibreOffice 25.2.6.2 (Linux)"/>
	<meta name="created" content="2025-10-28T11:36:21.445116225"/>
	<meta name="changed" content="2025-10-28T12:31:27.725833096"/>
	<style type="text/css">
		@page { size: 8.5in 11in; margin: 0.79in }
		p { margin-bottom: 0.1in; line-height: 115%; background: transparent }
		h1 { margin-bottom: 0.08in; background: transparent; page-break-after: avoid }
		h1.western { font-weight: bold; font-size: 18pt; font-family: "Liberation Sans", sans-serif }
		h1.cjk { font-weight: bold; font-size: 18pt; font-family: "Noto Sans CJK SC" }
		h1.ctl { font-weight: bold; font-family: "Noto Sans Devanagari"; font-size: 18pt }
		h2 { margin-top: 0.14in; margin-bottom: 0.08in; background: transparent; page-break-after: avoid }
		h2.western { font-weight: bold; font-size: 16pt; font-family: "Liberation Sans", sans-serif }
		h2.cjk { font-weight: bold; font-size: 16pt; font-family: "Noto Sans CJK SC" }
		h2.ctl { font-weight: bold; font-family: "Noto Sans Devanagari"; font-size: 16pt }
		a:link { color: #000080; text-decoration: underline }
	</style>
</head>
<body lang="en-US" link="#000080" vlink="#800000" dir="ltr"><p align="center" style="line-height: 100%; margin-top: 0.17in; margin-bottom: 0.08in; page-break-after: avoid">
<font face="Liberation Sans, sans-serif"><font size="6" style="font-size: 28pt"><b>Database
Back-end Server for GnuCash on a LAN or WAN</b></font></font></p>
<h1 class="western">Database Set-Up</h1>
<p style="line-height: 100%; margin-bottom: 0in"><br/>

</p>
<p style="line-height: 100%; margin-bottom: 0in">Set up the database
and then use the mysql client on another (test) system to make sure
you can access the DB -- before you try to connect GnUCash.</p>
<p style="line-height: 100%; margin-bottom: 0in"><br/>

</p>
<h2 class="western">For Linux Clients:</h2>
<p style="line-height: 100%; margin-bottom: 0in"><br/>

</p>
<p style="line-height: 100%; margin-bottom: 0in">Get the DB fully set
up and functional, and THEN you can install the dbi mysql dbd drivers
and then connect GnuCash to the MySQL via the correct URI.  (/THAT/
should be in the GnuCash docs/wiki).</p>
<p style="line-height: 100%; margin-bottom: 0in"><br/>

</p>
<h2 class="western">Other Client Systems:</h2>
<p style="line-height: 100%; margin-bottom: 0in"><br/>

</p>
<p style="line-height: 100%; margin-bottom: 0in">The client systems
will likely vary a bit, incorporating clients like mine, fedora and
windows vms, maybe a few other distros?  Maybe the odd Hackintosh?</p>
<p style="line-height: 100%; margin-bottom: 0in"><br/>

</p>
<p style="line-height: 100%; margin-bottom: 0in">Different clients
may have different requirements for getting the sql connectors
working.  YMMV.</p>
<p style="line-height: 100%; margin-bottom: 0in"><br/>

</p>
<p style="line-height: 100%; margin-bottom: 0in"><br/>

</p>
<p style="line-height: 100%; margin-bottom: 0in">References:</p>
<p style="line-height: 100%; margin-bottom: 0in"><br/>

</p>
<p style="line-height: 100%; margin-bottom: 0in">Chapter 2. The
Basics</p>
<p style="line-height: 100%; margin-bottom: 0in">2.4. Storing your
financial data</p>
<p style="line-height: 100%; margin-bottom: 0in"><a href="https://www.gnucash.org/docs/v5/C/gnucash-guide/basics-files1.html">https://www.gnucash.org/docs/v5/C/gnucash-guide/basics-files1.html</a></p>
<p style="line-height: 100%; margin-bottom: 0in"><br/>

</p>
<p style="line-height: 100%; margin-bottom: 0in"><a name="projectnumber"></a>
GnuCash &nbsp;5.6-150-g038405b370+</p>
<p style="line-height: 100%; margin-bottom: 0in"><a href="https://code.gnucash.org/docs/STABLE/group__Backend.html">https://code.gnucash.org/docs/STABLE/group__Backend.html</a></p>
<p style="line-height: 100%; margin-bottom: 0in"><br/>

</p>
<p style="line-height: 100%; margin-bottom: 0in"><br/>

</p>
</body>
</html>
