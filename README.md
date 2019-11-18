# DockerRegistry

Layer: Presentation
	- Instance: Presentation for Web (OS: Linux)
		- Web Application
		- API Gateway

	- Instance: Presentation for SFTP Server (OS: Windows)
		- SFTP Server

	- Instance: Presentation for Files Sharing (OS: Linux)
		- Files Sharing Server (e.g. Logo files)

Layer: Business
	- Instance: Business for API (OS: Linux)
		- Receipt Tax Invoice API (Duplicate by Corporate)
		- Abb Tax Invoice API (Duplicate by Corporate)
		- Credit Note API (Duplicate by Corporate)
		- Debit Note API (Duplicate by Corporate)
		- Master API (Duplicate by Corporate)
		- Web provider API
		- SMS service
		- Email service
		- Generate PDF API
		- ...
		
	- Instance: Business for Files Sharing (OS: Linux)
		- Files Sharing Server (e.g. Signature files, data.json, Pdf files)

	- Instance: GitLab (OS: Linux)
	- Instance: Docker Registry (OS: Linux)
	
Layer: Data
	- Instance: MSSQL Database (OS: Windows)
		- MSSQL
	
	- Instance: NoSQL Database(OS: Linux)
		- MongoDB
		- Redis
