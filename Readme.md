# End-User Designer - How to customize parameters in the Print Preview


This example demonstrates how to customize parameters displayed in the Print Preview of the End-User Designer. <br />The main idea is to use the <a href="https://documentation.devexpress.com/#XtraReports/DevExpressXtraReportsUserDesignerXRDesignMdiController_DesignPanelLoadedtopic">XRDesignMdiController.DesignPanelLoaded</a> event handler. In this event handler, subscribe to the ReportTabControl.PreviewReportCreated event where you can get a report instance by using the ReportTabControl.PreviewReport object. Use it to subscribe to the <a href="https://documentation.devexpress.com/#XtraReports/DevExpressXtraReportsUIXtraReport_ParametersRequestBeforeShowtopic">XtraReport.ParametersRequestBeforeShow</a> event. <br /><br />For more details, see <a href="https://www.devexpress.com/Support/Center/p/T210793">End-User Designer - How to customize parameters in the Print Preview</a>.

<br/>


