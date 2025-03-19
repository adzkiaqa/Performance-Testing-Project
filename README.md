# 🚀 Performance Testing Project - API Load & Stress Testing

Mini project ini bertujuan untuk menguji performa API menggunakan Apache JMeter.

## 🛠️ Tools
- Apache JMeter
- JMeter Plugins
- CSV Data Set Config
- Response Time Graph

## 🔍 Test Plan
### 1️⃣ Load Testing
- Simulasi **100 Virtual Users** dalam durasi **5 menit**.
- Mengukur **response time**, **error rate**, dan **throughput**.
- File: [`api-load-test.jmx`](test-plans/api-load-test.jmx)

### 2️⃣ Stress Testing
- Menambahkan **200+ Virtual Users** secara bertahap.
- Mengidentifikasi titik **bottleneck** dan **failure threshold**.
- File: [`api-stress-test.jmx`](test-plans/api-stress-test.jmx)

## 📊 Hasil Testing
| **Metric**   | **Load Test** | **Stress Test** |
|-------------|-------------|-------------|
| Avg. Response Time | 250ms | 900ms |
| Error Rate | 0.5% | 5% |
| Throughput | 120 req/sec | 60 req/sec |

**Grafik Hasil Performance Testing**  
📌 *Response Time Graph:*  
![Performance Graph](results/performance_graph.png)

📌 *Laporan Detail:*  
[Lihat Report JMeter](reports/jmeter-report.html)

## 🚀 Cara Menjalankan Test
1. **Clone repo ini:**
   ```sh
   git clone https://github.com/adzkiaqa/Performance-Testing-Project.git
   cd Performance-Testing-Project
