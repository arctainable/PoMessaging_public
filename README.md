# PoMessaging_public

![image](https://github.com/arctainable/PoMessaging_public/assets/84698429/78cbfc43-0588-45e8-96c3-1609d6022cd7)


ERP -> PO -> Legacy 통신 중 송수신은 정상적으로 성공하였으나 수신측의 로직상 이슈로 잘못된 데이터로 판단하여 에러 내역을 Response할 경우 ERP와 PO, Legacy 담당자에게 해당 내역을 메일로 보내주는 배치 프로그램

<div>import socket</div><div>
import smtplib</div><div> 
from email.mime.text import MIMEText</div><div>
import datetime</div><div>
import xlwings as xw</div><div>
import psycopg2</div><div>
import time</div><div>
import datetime</div><div>
import threading</div><div>
import time</div><div>
import re</div><div> 〓  </div>

* 1인 개발 
* 위 Library 사용
* 실제 코드는 private로 관리
* python으로 개발
