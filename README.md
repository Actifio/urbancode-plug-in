<h1>Actifio UrbanCode Deploy Plugin</h1>
<p>This project is a plugin for IBM's UrbanCode Deploy solution. The plugin allows process steps to be created that leverage the instant mount capabilities for Microsoft SQL Server and Oracle that Actifio's data management platform provides.</p>
<h2>Prequisites</h2>
<ul><li>Latest release of this plugin</a></li>
<li>IBM UrbanCode Deploy 6.2.7 or higher</li>
<li>Actifio virtual or hardware appliance version 7.1 or higher</li>
<li>Actifio Global Manager version 7.1 or higher</li></ul>
<h2>Installing</h2>
<ul><li>Login to the UrbanCode console</li>
<li>Navigate to Settings -> Automation Plugins</li>
<li>Click the 'Load Plugin' button</li>
<li>When prompted, click the 'Choose File' button</li>
<li>Select the downloaded zip file and then click 'Submit'</li></ul>
<h2>Using</h2>
<ul><li>Login to the UrbanCode console</li>
<li>Navigate to Components and create a new or select an existing component</li>
<li>On the component details page select the 'Processes' tab</li>
<li>Create a new or select an existing process</li>
<li>In the Process designer navigate to the Actifio entry in the sidebar menu</li>
<li>Drag and drop a step from the Provision Database category onto the layout</li>
<li>Click the edit icon for the step and enter the required information</li></ul>
<h2>Limitations</h2>
<ul><li>Transaction log roll forward not supported</li>
<li>SQL Server instance level mount not supported</li>
<li>Individual SQL Server database mount from instance level capture not supported</li></ul>
<h2>License</h2>
<p>Copyright 2018 Anthony Golia anthony.golia@actifio.com</p>
<p>Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:</p>
<p>The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.</p>
<p>THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.</p>
