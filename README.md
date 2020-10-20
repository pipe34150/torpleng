# TorPleng

การต่อเพลงไทยที่ยาวที่สุดในประวัติศาสตร์

## Rules

- เนื้อเพลงที่มาต่อ ต้องมีความยาวอย่างน้อย 1 ประโยค และจบด้วยคำสุดท้ายของประโยคนั้น
- คำหรือวลีที่มาต่อ ต้องเป็นคำเดียวกับคำสุดท้ายของเพลงที่แล้ว หรือพ้องเสียง
- เป็นเพลงไทย ที่มีคลิปบนเว็บ Youtube แนบคลิปพร้อมเวลาของท่อนเพลงที่จะใช้
- กฎอาจมีการเพิ่มเติม หรือยกเว้น ตามความเหมาะสม
- ไม่ใช้ท่อนเดิม จากเพลงเดิมซำ้
- เรียงลำดับเพลงจาก Pull Request ที่เปิดก่อน
- หากท่อนล่าสุดไม่สามารถต่อได้ หรือต่อยาก จะมีข้อยกเว้นให้ตามลำดับ
  - เพิ่มท่อนเพลงล่าสุดอีก 1-2 ประโยค เพื่อเปลี่ยนคำที่จะมาต่อ
  - อนุโลมให้ใช้คำที่ 2 หรือ 3 ของเพลงที่มาต่อได้ โดยใส่วงเล็บครอบคำที่ข้ามไป [ตัวอย่าง](https://github.com/narze/torpleng/pull/27)
  - ให้นำท่อนล่าสุดออกและเปลี่ยนเพลงได้ (ไม่แนะนำ เพราะเป็นการลบเพลงของคนอื่น)

## Pull Request

เปิด Pull Request ด้วยข้อมูลดังนี้

- เนื้อเพลงที่นำมาต่อ
- ชื่อเพลง
- ชื่อศิลปิน หรือวง
- ลิงก์ของคลิป Youtube พร้อมเวลาของท่อนเพลงที่นำมาต่อ โดยตัด Query String อื่นๆ ออก เช่น https://www.youtube.com/watch?v=T6F6hOKPCo4&t=71

## Features (TODO)

- Render with HTML (Vue.js)
- Validate with Github Actions

## Entries

- ขวัญเจ้าเอยขวัญมาใยหนอล่องลอยหลุดไป อยู่ที่ไหนช่วยบอกได้ไหมใจ ใยถึงไม่คืนกลับมา [Palmy - ขวัญเอยขวัญมา](https://youtu.be/T6F6hOKPCo4?t=71)
- กลับมาได้หรือเปล่า กลับมาหาฉันทีได้ไหมคนดี [2 Day ago Kids - กลับมา](https://youtu.be/8M9N_eZh4KQ?t=70)
- ดีแล้ว ที่เธอกระทำอยู่ทุกวันนี้ [สหายแห่งสายลม - ดีแล้ว](https://youtu.be/52rn8wsfxSM?t=39)
- วันนี้ วันไหน อยากให้เธอมั่นใจ ว่าไม่ว่าเธอฝันอย่างไหน แม้มันจะไกลสุดไกลเท่าไร [Bodyslam - ทางของฉัน ฝันของเธอ](https://youtu.be/TgvXisKG2CY?t=47)
- เท่าไหร่ก็ไม่จำ ไม่สำคัญ แค่ฉันลืมตามาพบเธอ เหมือนแสงส่องทาง ที่ดูงดงาม เหมือนเป็นคำถาม ที่คำตอบก็คือเธอ [POTATO - เท่าไหร่ไม่จำ](https://youtu.be/UHKS37Inpdc?t=203)
- เธอ เธอยังคิดถึงฉันไหม เมื่อสองเรานั้นยังคงห่างไกล เมื่อเวลาพาเราให้ไกลกัน รู้บ้างไหมคนไกลยังคงหวั่นไหว เมื่อเขามองดูภาพเธอทีไร น้ำตามันยังไหลออกมา [COCKTAIL - เธอ](https://youtu.be/nY9sHiZ4bTU?t=88)
- มาทำไมให้อายบ้านนา เล่านวลน้อง ไม่ต้องกลับคืนมา [ทิดเซียง - กลับมาทำไม](https://youtu.be/tw5LTC__YWk?t=24)
- มารักทำไมตอนนี้ ตอนที่จะเสียฉันไป ทั้งๆ ที่ฉันทุ่มให้หมดใจ แต่เธอกลับทิ้งมัน [Am Fine - มารักทำไมตอนนี้](https://youtu.be/maz6gnq-n6g?t=12)
- มันเจ็บจะขาดใจอยู่ตรงหน้าเธอ แต่ต้องเก็บไว้ไม่แสดงว่าเสียใจ [Pancake - ขาดใจ](https://youtu.be/l9MRG7XV3V0?t=43)
- ใจมันยังเกเรเสมอไม่เคยจะเชื่อฟัง [Nice 2 Meet U - ใจเกเร](https://youtu.be/zDQeip3CPzI?t=103)
- ฟังเสียงใครต่อใครมากกว่าหัวใจตัวเราเองสวยงามคนเราแล้วแต่ใจใคร [SIN feat. โอม Cocktail - ฟัง](https://youtu.be/f05VJ1moOKE?t=162)
- ใครกันที่ทำให้ฉันรัก ใครกันที่มาอยู่ในความฝัน คนที่ฉันคิดถึงอยู่ทุกวัน ก็ใครคนนั้น ฉันเรียกว่าเธอ [ALL KAMIKAZE - รักฉันเรียกว่าเธอ](https://youtu.be/iRCb_PodGfQ?t=13)
- เธอยังคิดถึงฉันทุกนาทีอยู่หรือเปล่า เธอยังจำเรื่องเราในวันวานได้หรือไม่ เธอยังมีใจให้ฉันคนเดียว ยังรอฉันแค่คนเดียว เธอยังคงเป็นเหมือนเดิมอยู่ใช่ไหม ช่วยบอกให้รู้ที [POTATO - เธอยัง](https://www.youtube.com/watch?v=bNVxKaPxr6w)
- ทีใครทีมัน หนทางยังอีกไกล คราวใครคราวมัน วัดกันไปจนวันสุดท้าย วันสุดท้าย ฮูว ฮูว..[25hours - ทีใครทีมัน](https://youtu.be/hFse57E5Bw8?t=47)
- Hula Hula, Hoo la la la ไปทะเล Hoorey Hoorey, Yeah yeah ทุกเวลา [HULA HULA - 2005 ทิวา Hula Hula](https://youtu.be/BQHL4rwGc68?t=16)
- เวลาที่เราได้มองตากัน ไม่รู้ว่าเธอสงสัยฉันบ้างไหม ว่าใครคนนึงเฝ้ามองเธออยู่ และเขาก็อยากให้เธอได้รู้ใจ [Whal&Dolph - ใจเดียว](https://youtu.be/p5CsJurJ5Lo?t=89)
- ใจฉันไม่ได้รู้สึก เหมือนครั้งที่เราได้เจอกันเมื่อก่อนนั้น [Whal & Dolph - ไม่รู้ทำไม](https://youtu.be/CCxlsWFH3Nc?t=39)
- (เมื่อเรา)นั้นคิดจะปิด ทุกความสัมพันธ์ใดๆ ร่างกายมีเพียงแค่ฉันและเธอ [Musketeers - ใจความสำคัญ](https://youtu.be/rw1BXzZgoPc?t=37)
- เธอ เธอทั้งนั้นที่ทำ ให้ช่วงชีวิตของฉันน่าจดจำ [Groove Riders - เธอทั้งนั้น](https://youtu.be/f-eE1z1Pv7Y?t=40)
- จำเก่งจนไม่เคยลืมเธอ [F.HERO x Tilly Birds - จำเก่ง](https://youtu.be/7iSia7rb1PY?t=92)
- เธอไม่เคยเอ่ยคำว่ารักกัน มีแต่ฉันที่คิดไปฝ่ายเดียว ที่อยู่กับฉันใช้เวลาด้วยกัน นั่นเพียงฉันแค่คิด [ส้ม มารี - หรือฉันคิดไปเอง](https://youtu.be/UfgPHAZD5e0?t=65)
- คิด(แต่ไม่) ถึง คิด คิด(แต่ไม่) ถึงเธอ [Tilly Birds - คิด(แต่ไม่)ถึง [Same Page?]](https://youtu.be/dJ9uVVNWClk?t=38)
- เธอคงไม่รู้ ว่าฉันเองยังไม่มีใคร หากเป็นเธอ ก็คงเข้าที เธออาจจะมีใคร คนนั้นที่แสนดี [LOSO - ฝนตกที่หน้าต่าง](https://youtu.be/SXy-v1KbF4k?t=53)
- ดีแล้วได้อะไร เมื่อใจทั้งใจ เธอให้เขา [KOOKKI - ดีแล้วได้อะไร](https://youtu.be/Kzr04RysKdI?t=33)
- เขาเดินจากไปแล้วไม่ต้องคิดถึง ไม่ต้องนึกถึงเขาอีกแล้ว [wonderframe - เขาไปแล้ว](https://youtu.be/paIrJvhXFXU?t=71)
- แล้วฉันเลือกอะไรได้ไหม เลือกให้เธอไม่ไปได้หรือเปล่า [ZAZA - เลือกได้ไหม](https://youtu.be/xoP_kqiqRgM?t=112)
- เปล่า ไม่มีเขานอกเหนือจิตใจ ไม่มีรัก จะหลงผู้ใด [เปล่า - สุนทราภรณ์ ](https://youtu.be/CsIdMaYOQZk?t=53)
- ด่ำด่าดีดำดำด๊ำด๊ำดำ ด้ำด้าดีดำด่ำด๊ำด๊ำดำ ด่ำด่าดีดำดำด๊ำด๊ำดำ ด้ำด้าดีดำด่ำด๊ำด๊ำดำ [forever - ดำดีดูดี](https://www.youtube.com/watch?v=iMicTF2LMb8)
<!-- เพิ่มเพลงด้านบนบรรทัดนี้ format : เนื้อเพลง [ศิลปิน - ชื่อเพลง](Youtube link with timestamp) -->
