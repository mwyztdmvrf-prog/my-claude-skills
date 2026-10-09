# my-claude-skills

ที่เก็บ skill (คู่มือการทำงาน) สำหรับ Claude

## มีอะไรอยู่ในนี้

| Skill | ที่อยู่ | ใช้ทำอะไร |
|---|---|---|
| `claude-api` | `.claude/skills/claude-api/` | ช่วยเขียนโค้ดเรียกใช้ Claude API และสร้าง Managed Agent |

คัดลอกมาจาก [anthropics/skills](https://github.com/anthropics/skills/tree/main/skills/claude-api)
(commit `683bc88`, PR [#1962](https://github.com/anthropics/skills/pull/1962))
ใช้สัญญาอนุญาต Apache 2.0 ตามไฟล์ `.claude/skills/claude-api/LICENSE.txt`

## วิธีใช้

1. เปิด [claude.ai/code](https://claude.ai/code) แล้วเลือก repo นี้
2. พิมพ์คำสั่งใดคำสั่งหนึ่ง:

- `managed-agents-onboard` ให้ Claude ถามทีละข้อเพื่อสร้าง agent ตั้งแต่ศูนย์
- `managed-agents-onboard deep-researcher` สร้างจากแม่แบบสำเร็จรูป
- `managed-agents-onboard <ลิงก์>` สร้างตามรูปแบบที่หน้าเว็บนั้นอธิบาย

แม่แบบที่มีให้เลือก: `contract-tracker`, `data-analyst`, `deep-researcher`,
`field-monitor`, `incident-commander`, `sprint-retro-facilitator`,
`structured-extractor`, `support-agent`, `support-to-eng-escalator`

ต้องมี API key จาก [Claude Console](https://platform.claude.com) ก่อนจึงจะสร้าง agent ได้จริง

## อัปเดตเมื่อต้นฉบับเปลี่ยน

สั่ง Claude ว่า "อัปเดต skill claude-api จาก anthropics/skills ให้เป็นเวอร์ชันล่าสุด"
