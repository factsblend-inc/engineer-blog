### รายงานเหตุการณ์ระบบขัดข้อง - 20 ตุลาคม 2025
### System Incident Report - October 20, 2025

วันที่เกิดเหตุ (Incident Date): 20 ตุลาคม 2025\
ระยะเวลาที่ได้รับผลกระทบ (Affected Duration): 15:00 -- 16:00 (GMT+7)\
สถานะปัจจุบัน (Current Status): ระบบกลับมาให้บริการได้ตามปกติแล้ว / All systems have been fully restored and are now operating normally.

* * * * *

### สาเหตุของเหตุการณ์ (Root Cause)

ทีมงานตรวจสอบพบว่า เหตุการณ์ในครั้งนี้เกิดจากปัญหาการให้บริการของผู้ให้บริการโครงสร้างพื้นฐาน Amazon Web Services (AWS) และ Vercel ซึ่งเกิดเหตุขัดข้องระดับโลกเมื่อวันที่ 20 ตุลาคม 2025 ตามรายงานข่าวจากสำนักข่าว CNN และ Reuters ([CNN Live Update](https://edition.cnn.com/business/live-news/amazon-tech-outage-10-20-25-intl), [Reuters Report](https://www.reuters.com/business/retail-consumer/amazons-cloud-unit-reports-outage-several-websites-down-2025-10-20/?utm_source=chatgpt.com))

เหตุการณ์นี้ส่งผลให้ เว็บสั่งอาหาร (Web Ordering System) และ เว็บจัดการร้านอาหาร (Restaurant Management Portal) ซึ่งทำงานอยู่บนระบบดังกล่าว ได้รับผลกระทบชั่วคราวและไม่สามารถให้บริการได้ตามปกติในช่วงเวลาที่ระบุ

Root Cause (English):\
After investigation, the engineering team identified that the incident was caused by a global outage from our infrastructure providers, Amazon Web Services (AWS) and Vercel, on October 20, 2025, as reported by [CNN Live News](https://edition.cnn.com/business/live-news/amazon-tech-outage-10-20-25-intl) and [Reuters](https://www.reuters.com/business/retail-consumer/amazons-cloud-unit-reports-outage-several-websites-down-2025-10-20/?utm_source=chatgpt.com).\
This disruption temporarily affected both our Web Ordering System and Restaurant Management Portal, causing service unavailability during the specified period.

* * * * *

### แผนป้องกันในอนาคต (Preventive Actions)

เพื่อป้องกันไม่ให้เหตุการณ์ลักษณะนี้ส่งผลกระทบต่อผู้ใช้งานในอนาคต ทางทีมงานได้วางแผนและเริ่มดำเนินการโดยทันที ดังนี้

1.  เพิ่มผู้ให้บริการ Cloud รายที่สอง เพื่อสร้างระบบ Multi-Cloud Architecture สำหรับสำรองและกระจายการทำงานของบริการสำคัญ
2.  ปรับปรุงระบบ Monitoring & Failover เพื่อให้สามารถตรวจจับและตอบสนองได้รวดเร็วยิ่งขึ้น
3.  ทบทวนขั้นตอน Disaster Recovery Plan (DRP) เพื่อให้มั่นใจว่าสามารถรักษาความต่อเนื่องของบริการได้แม้ในกรณีที่เกิดเหตุไม่คาดคิด

Preventive Actions (English):\
To prevent similar issues from impacting our users in the future, our team has immediately initiated the following measures:

1.  Implement Multi-Cloud Architecture --- Add a secondary cloud provider to improve redundancy and ensure continuous service availability.
2.  Enhance Monitoring & Failover Systems --- Upgrade detection and automatic recovery processes for faster response during service disruptions.
3.  Review and Strengthen Disaster Recovery Plan (DRP) --- Ensure business continuity even in the event of unexpected outages.

* * * * *

### คำขอโทษและคำมั่นสัญญา (Acknowledgement)

ทีมงานขออภัยในความไม่สะดวกที่เกิดขึ้นจากเหตุการณ์ครั้งนี้ เราตระหนักถึงความสำคัญของความเสถียรและความต่อเนื่องในการให้บริการ และขอยืนยันว่าทีมงานจะดำเนินการปรับปรุงระบบอย่างต่อเนื่อง เพื่อให้ลูกค้าได้รับประสบการณ์การใช้งานที่ดีที่สุด

Acknowledgement (English):\
We sincerely apologize for the inconvenience caused by this incident. We understand the importance of service stability and continuity, and we remain fully committed to enhancing our system reliability to deliver the best possible experience for our users.

* * * * *

ขอแสดงความนับถือ / Sincerely,\
Chayut Dookandee

Chief Technology Officer (CTO)\
Factsblend Company Limited
