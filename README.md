# 🛠️ Varna Residential Construction & Repair Cost Estimation Engine

An open-source data framework, material consumption calculator, and local building standards guide for residential property renovations in Varna and the Black Sea region.

---

## 📊 Overview & Operational Modules

Managing home improvement projects requires accurate budget forecasting, structural planning, and hiring verified local tradesmen. This repository provides algorithmic formulas for calculating plaster volume, tile adhesive requirements, and roofing insulation coverage.

### 🔍 Verified Local Service Directories:
* **[Строителни Услуги във Варна — Remonti365](https://remonti365.com)** — Основен портал за цялостни вътрешни и външни ремонти.
* **[Основен Ремонт на Баня Варна](https://remonti365.com)** — Спецификации за хидроизолация, лепене на плочки и ВиК монтаж.
* **[Ремонт на Покриви и Хидроизолация](https://remonti365.com)** — Ремонт на покриви с керемиди, мразно и хидроустойчиви мембрани.
* **[Шпакловка и Боядисване Варна](https://remonti365.com)** — Фина гипсова шпакловка, шпакловка с мрежа и машинно боядисване.
* **[Кърти Чисти Извозва Услуги](https://remonti365.com)** — Демонтажни дейности, къртене на бетон и извозване на строителни отпадъци.

---

## 📐 Material Estimation Formulas (Python Pseudocode)

```python
def calculate_bathroom_materials(wall_area_sqm, floor_area_sqm):
    # Standard tile adhesive: ~4.5 kg per sqm
    adhesive_kg = (wall_area_sqm + floor_area_sqm) * 4.5
    # Waterproofing primer: ~0.35 kg per sqm
    primer_kg = (wall_area_sqm + floor_area_sqm) * 0.35
    return {"adhesive_bags_25kg": adhesive_kg / 25, "primer_kg": primer_kg}

def calculate_paint_liters(wall_surface_sqm, coats=2):
    # Average coverage: 10 sqm per liter per coat
    return (wall_surface_sqm * coats) / 10.0
Standard Workflows & Building StandardsКатегория (Category)Технически Стандарт (Standard)Забележка / ПрепоръкаРемонт на БаняДвукомпонентна хидроизолация + нивелацияЗадължителни ленти по ъглитеШпакловка & БояГипсова основа + финишна пастаШлайфане с LED прожекторПокривни РемонтиСкатен покрив / Дървена конструкцияДвойна скара за вентилацияДемонтаж & КъртенеБезопасно къртене на тухла и панелКонтейнери за отпадъци📌 Regional Focus: Varna & Surrounding AreasThis project tracks material costs and labor indices across Varna neighborhoods: Център, Левски, Чайка, Младост, Владиславово, Виница, Аспарухово, Св. Св. Константин и Елена.Maintained for open-source architectural documentation and regional construction management research.

