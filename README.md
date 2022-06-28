# reconciliation

Dashboard to identify all of the failed events from all the downstream systems and provide an option to retry for the failed events as well.


Event Object Structure
	{
  "id": "7fdfe6b0-5d17-406d-93c2-2afc0abb977e",
  "source": "",
  "type": "",
  "status": "",
  "timestamp": "",
  "refNum": "",
  "errorCode": "",
  "errorDescription": "",
  "eventCode": "",
  "runId": "”
}

Backend
 API to see all the available events.
 Filtering and Pagination support for API.
 API to get a particular event detail.
 API to reconcile a particular event. (Feature flag.)
 Authentication and Authorization for APIs.
