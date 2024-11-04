   
    พิมพ์ เพื่อเปิด
        docker-compose up -d

    เพื่อปิด
        docker-compose down

    เพื่อลบข้อมูล databases ทิ้ง
        docker volume rm <ชื่อโฟสเดอร์_ชื่อvolumes> 
        เช่น docker volume rm strat_judJamPostgresData

    ตรวจสอบ ที่ run อยู่
        docker ps