# YOSUGA — Product Specifications (Concept)

**VÄLK NØVA AXIOM · VÄLK NØVA ELEMENT · LÜMEN MONAD**  
**Status: Preliminary design targets / 構想仕様**  
**Last updated: 2026-11-17**

> **Important / 重要**  
> All specifications on this page describe **proposals and development targets**, not completed products. Components, performance, certifications, manufacturing feasibility, and availability have **not been confirmed**. This document is a public-facing summary, not a final engineering requirements document.  
> このページの数値・機能はすべて**構想または開発目標**です。部品の調達可否、性能、量産性、各種認証などは未確認であり、最終製品仕様を示すものではありません。

## 01 — VÄLK NØVA smartphones / スマートフォン

### Hardware / 基本仕様

| Item / 項目 | **NØVA AXIOM** | **NØVA ELEMENT** |
|---|---|---|
| Positioning / 位置づけ | Flagship / フラッグシップ | Accessible model / 普及価格帯 |
| Display / 画面 | 7.1-inch LTPO OLED, up to 144Hz (target) | 6.4-inch OLED, up to 120Hz (target) |
| Display resolution / 解像度 | TBD / 未定 | Approx. 1.5K, subject to review / 約1.5K検討 |
| SoC / プロセッサ | Next-generation Snapdragon flagship candidate (tentatively **Snapdragon 8 Elite Gen 6**) | **Snapdragon 7 Gen 4** candidate |
| Memory / RAM | 16GB, LPDDR5X target | 12GB, LPDDR5X target |
| Internal storage / 内蔵ストレージ | 512GB, UFS 4.1 target | 256GB, UFS 3.1-class target |
| Expandable storage / 外部ストレージ | microSD support planned | microSD support planned |
| OS / OS | **ÆTHER**, Android-based | **ÆTHER**, Android-based |
| Navigation / 独自操作 | **DialNav** rear ring controls | **DialNav** rear ring controls |
| Rear fingerprint sensor / 背面指紋認証 | Planned, central camera module concept | Planned; placement TBD |
| Stereo speakers / スピーカー | Stereo; premium acoustic tuning target | Stereo; quality-focused tuning target |
| Headphone jack / イヤホン端子 | **3.5mm** | **3.5mm** |
| DAC / ヘッドホン音響 | High-quality DAC and amplifier circuit; model TBD | High-quality DAC and amplifier circuit; model TBD |
| Rear finishes / 背面仕上げ | **CHROMA 23** concept | **CHROMA 23** concept |
| Dust/water resistance / 防水防塵 | **IP68 target**, not certified | **IP68 target**, not certified |
| Durability / 耐久性 | MIL-STD-810H-based test program proposed; not tested | MIL-STD-810H-based test program proposed; not tested |

### Cameras / カメラ構想

| Camera / カメラ | **NØVA AXIOM** | **NØVA ELEMENT** |
|---|---|---|
| Main / メイン | 200MP candidate, OIS target (Sony LYTIA 901 under consideration) | 200MP Samsung ISOCELL HP5 candidate, OIS target |
| Ultra-wide / 超広角 | 200MP candidate (Samsung ISOCELL HP5 under consideration) | 13MP OmniVision OV13B10 candidate, AF target |
| Telephoto / 望遠 | 200MP candidate, proposed **switchable 3× / 6× optical** system (Samsung ISOCELL HP9 under consideration) | 50MP Sony IMX882 candidate, **3× optical** and close-focus telemacro target, OIS target |
| Macro / マクロ | Separate 200MP macro camera concept (Samsung ISOCELL HP5 under consideration) | Telephoto/telemacro combined concept |
| Front camera / インカメラ | TBD / 未定 | 32MP OmniVision OV32B candidate; autofocus under review |
| Dedicated shutter / シャッター | Two-stage physical shutter proposed | TBD / 未定 |
| Camera arrangement / カメラ配置 | Large circular module; mechanical and optical design TBD | TBD / 未定 |

**Camera feasibility note / カメラに関する注記:** The proposed sensor combinations, four 200MP modules, switchable optical telephoto mechanism, and camera packaging are **unverified**. Availability, image processing support, power, thermals, optical constraints, and cost require engineering validation.  
4基の200MPセンサー、可変望遠機構、各モジュールの組み合わせは**実装・調達を保証するものではありません**。ISP対応、光学設計、放熱、消費電力、部品サイズ、費用などを検証する必要があります。

### Charging & connectivity / 充電・接続

| Item / 項目 | **NØVA AXIOM** | **NØVA ELEMENT** |
|---|---|---|
| Battery / 電池 | ~6,000mAh target | ~5,500mAh target |
| Wired charging / 有線充電 | Up to **165W** design target; charging protocol TBD | **45W USB PD PPS** target |
| Wireless charging / 無線充電 | **Qi2 25W** target | **Qi2 15W** target |
| Magnetic alignment / 磁気吸着 | Built-in magnets planned | Built-in magnets planned |
| USB data / USB転送 | USB 3.2 Gen 2, up to 10Gbps target | USB 3.2 Gen 1, up to 5Gbps target |
| External video / 外部映像出力 | USB-C DisplayPort Alt Mode target | USB-C DisplayPort Alt Mode target |
| Cellular / モバイル通信 | 5G support targeted; bands TBD | 5G support targeted; bands TBD |
| SIM / SIM構成 | TBD; dedicated microSD slot preferred | TBD; dedicated microSD slot preferred |
| Other connectivity / その他 | Wi-Fi, Bluetooth, NFC/FeliCa specifications TBD | Wi-Fi, Bluetooth, NFC/FeliCa specifications TBD |

**Charging and certification note / 充電・認証に関する注記:** Qi2 support and power levels are **targets**, not claims of Wireless Power Consortium certification. The proposed AXIOM 165W wired-charging solution would require separate electrical, thermal, battery-safety, and USB-PD compatibility evaluation.  
Qi2認証は未取得です。AXIOMの165W充電は方式・発熱・電池寿命・安全性・USB PDとの互換性を含めて検証が必要です。

### Design & software / デザイン・ソフトウェア

| Area / 項目 | Concept / 構想 |
|---|---|
| **CHROMA 23** | Shared collection of 23 proposed colors/material finishes, including special textures, optical effects, wood veneers, and a transparent concept / 23種類の特殊仕上げ |
| Surface patterns / 背面模様 | Two-layer geometry: precise micro-patterns + expressive large-scale shapes / 精密な微細模様と大胆な大型模様 |
| **DialNav** | Rear touch/control ring concept; integration and interference to be validated / 背面リング型の操作機構 |
| **ÆTHER** | Experimental Android-based operating system with original gestures, animations, and hardware integration / Androidベースの独自OS |
| Desktop use / 外部画面利用 | Potential future ÆTHER desktop interface; not a confirmed software feature / デスクトップUIは将来構想 |
| Repairability / 修理性 | Battery replacement by qualified service personnel and long-term parts support under consideration / 修理対応と部品供給を検討 |

---

## 02 — LÜMEN MONAD digital camera / 独立型デジタルカメラ

**MONAD is a standalone fixed-lens digital camera, not a smartphone.**  
MONADはスマートフォンではなく、独立したレンズ一体型デジタルカメラの構想です。

| Item / 項目 | **LÜMEN MONAD — Development Target** |
|---|---|
| Camera type / 種別 | Dedicated, premium, fixed-lens digital camera / 高級レンズ一体型カメラ |
| Image sensor / センサー | 35mm full-frame CMOS (~36 × 24mm) / 35mmフルサイズ |
| Native image resolution / ネイティブ画素数 | Approx. **60MP** / 約6000万画素 |
| High-resolution mode / 高解像度撮影 | Approx. **240MP** multi-shot sensor-shift composite, concept only / センサーシフト合成で約2億4000万画素構想 |
| Lens / レンズ | Non-interchangeable **35mm F1.8** prime lens / 交換不可の35mm F1.8単焦点 |
| Lens structure / レンズ構造 | Permanently protruding, non-retractable lens; removable lens cap / 非沈胴式・レンズキャップあり |
| Viewfinder / ファインダー | Hybrid optical/electronic (OVF/EVF) concept / 光学・電子切り替え構想 |
| Body / ボディ | Dedicated camera body with grip and physical controls / グリップ・物理操作を備えたカメラ型ボディ |
| Shutter controls / シャッター操作 | Two-stage physical shutter button proposed / 2段階シャッター構想 |
| Processor / 画像処理 | TBD / 未定 |
| Storage / 記録メディア | TBD / 未定 |
| Stabilization / 手ブレ補正 | Sensor-shift mechanism under consideration; implementation TBD / センサーシフト検討中 |
| Video / 動画機能 | TBD / 未定 |
| Power / 電池・充電 | TBD / 未定 |
| Release date / 発売時期 | Not announced / 未定 |

**Optical feasibility note / 光学技術に関する注記:** The hybrid OVF/EVF arrangement and ~240MP sensor-shift composite are particularly ambitious. Optical alignment, parallax, mechanical packaging, and processing requirements remain open engineering questions.  
ハイブリッドファインダーや高解像度合成撮影の実現性は未検証です。

---

## 03 — Development status / 開発状況

| Category / 分野 | Status / 状態 |
|---|---|
| Product design / 製品仕様 | Concept and requirement definition / 構想・要求仕様検討中 |
| ODM / 製造協力 | Exploring potential partners; no partnership announced / 協力先を検討中・契約未発表 |
| ÆTHER OS | Experimental development / 実験的開発中 |
| Hardware prototypes / 実機試作 | No completed commercial prototypes announced / 商用試作機完成の発表なし |
| Regulatory approvals / 認証 | Not obtained / 未取得 |
| Production & release / 量産・発売 | Not scheduled or confirmed / 未定 |

### Public-information notice / 公開情報に関する注意

- Component names identify **possible candidates**, not supplier commitments or confirmed sourcing. / 部品名は候補であり、調達契約を意味しません。
- Product and technology names are used to describe project intentions; they do not imply endorsements or cooperation by other companies. / 他社との提携を示すものではありません。
- Detailed mechanical drawings, circuits, supplier negotiations, and non-public engineering requirements are deliberately excluded. / 詳細な図面・回路・取引情報は掲載していません。
- YOSUGA is a project in preparation and **is not yet an incorporated company**. / YOSUGAは法人設立前です。

[← Back to README / READMEに戻る](README.md)

---

© 2026 YOSUGA Project. Specifications are subject to change.
