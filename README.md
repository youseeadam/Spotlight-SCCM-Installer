# Spotlight-SCCM-Installer
Designed to deploy Spotlight via SCCM
<p>
  The combined package can be found under the Releases tab.
  <ol>
    <li>Download the file Logitech Spotlight Combined.zip</li>
    <li>Copy the Logitech Spotlight_files to your distribution share</li>
    <li>Import the Logitech Spotlight.zip into your SCCM applications</li>
    <li>When you import the configuration an error will occure, choose to ignore the errors</li>
    <li>Go the properties of the Application</li>
    <li>Edit the deployment type of Logitech Presenter Software</li>
    <li>Change the Content location to match your configuration (where you extracted the Spotlight_files above</li>
    <li>Deploy and Distribute the application</li>
    </ol>
    </p>
    <p>
  <B>Note:</B> This application will import an condition to detect if the spotlight is connected, this will ensure it only is deployed to devices with a Spotlight attached. If you do not want this condition remove the requirment from the application deployment type.</p>
