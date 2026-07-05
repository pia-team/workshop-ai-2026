# Katılımcı Ödevleri — AI Agent Projeleri

Workshop sonrası ödevimiz sade ve netti: **istediğiniz dilde, LLM ile çalışabilen bir AI Agent geliştirin.**

Ödevi tamamlayıp reposunu paylaşan tüm katılımcılara gönülden teşekkürler. Bir workshop'un
gerçek çıktısı slaytlar değil, sonrasında üretilen projelerdir — aşağıdaki liste tam olarak bu.
Her repo, kendi yaklaşımı ve kendi teknoloji seçimleriyle agent mimarisine farklı bir pencere açıyor.
Her projeyi derinlemesine incelemenizi, yıldızlamanızı ve fikir alışverişi yapmanızı öneriyorum. 
Özellikle projelere issue, PR gibi eklemeler yaptım(katılımcılara yol-haritası olsun istiyorum, learning-path)

## Paylaşılan Projeler

Liste paylaşım sırasına göredir — ilk paylaşan ilk sıradadır.

| # | Katılımcı | Repo | Dil / Stack | Açıklama |
|---|-----------|------|-------------|----------|
| 1 | [Nida Duman](https://github.com/Nidadmn) | [smart-agent](https://github.com/Nidadmn/smart-agent) | Python, Ollama | Framework kullanmadan sıfırdan yazılmış minimal otonom agent: planlama, tool kullanımı ve execution loop. |
| 2 | [Şeyma Nalbant](https://github.com/nalbantseymaa) | [telco-ai-agent](https://github.com/nalbantseymaa/telco-ai-agent) ・ [video](https://drive.google.com/file/d/1q6h2KgiJwF3XZUNW_rr-UAx8TMTvTQDb/view) | Python, LangChain, Groq | LibreDB/PostgreSQL üzerindeki telekom telemetri verisini analiz eden ve müşteri kaybını (churn) azaltmaya yönelik aksiyon üreten cognitive agent. |
| 3 | [Tuba Çınar](https://github.com/tubacayir) | [research-data-collector-agent](https://github.com/tubacayir/research-data-collector-agent) | Python | Verilen araştırma konusu için otomatik veri toplayan araştırma asistanı agent'ı. |
| 4 | [Kadriye Işık](https://github.com/kadriyeisik) | [telecomops-ai-agent](https://github.com/kadriyeisik/telecomops-ai-agent) | Java (Spring Boot), React, OpenAI, Ollama | Telecom AI agent that autonomously diagnoses customer network issues using tool calling, supports OpenAI and Ollama models, and provides explainable diagnostic workflows with actionable resolutions. |
| 5 | [İrem Tuğba Sağsöz](https://github.com/iremsagsoz) | [ai-code-review-agent](https://github.com/iremsagsoz/ai-code-review-agent) | Python, FastAPI, Gemini API | Python dosyalarını veya projelerini Google Gemini API ile analiz eden, güvenlik ve kod kalitesi değerlendirmeleri yaparak detaylı rapor oluşturan AI Code Review Agent. |
| 6 | [Cennet Akçakaya](https://github.com/Cennetaakcakaya) | [gunluk-asistan-chatbot](https://github.com/Cennetaakcakaya/gunluk-asistan-chatbot) | Python, Streamlit, Groq API | Günlük planlama, ders çalışma programı hazırlama, yemek önerileri, motivasyon desteği ve mesaj taslakları oluşturan LLM tabanlı günlük yaşam asistanı. |
| 7 | [Zeliha Polat](https://github.com/zelihapp) | [deep-learning-model-management-agent](https://github.com/zelihapp/deep-learning-model-management-agent) | Python, Ollama | Framework kullanmadan yazılmış, eğitim loglarını analiz eden, modelleri karşılaştıran ve hiperparametre önerisi sunan agent. |
| 8 | [Aybüke Şenel](https://github.com/aybuke-senel) | [QuietScript](https://github.com/aybuke-senel/QuietScript) | Python, Ollama, Qwen 2.5 | Yerel çalışan LLM ile metin analizi, yazı geliştirme ve yazma desteği sunan AI agent'ı. |
| 9 | [Elif Nur Akyol](https://github.com/enurakyol) | [project-planning-agent](https://github.com/enurakyol/project-planning-agent) | Python, Google GenAI SDK | Google Gemini kullanarak farklı projeler için kapsamlı proje planı oluşturan yapay zeka ajanı. |
| 10 | [Nimet Atila](https://github.com/nimetbuse07) | [telecom_support_agent](https://github.com/nimetbuse07/telecom_support_agent) | Python, LangChain, Groq | Müşteri şikayetlerini analiz edip, gerçek zamanlı veritabanı sorgularıyla teşhis koyan ve gerektiğinde otonom olarak saha ekibi kaydı açan bilişsel asistan. |
| 11 | [Esra Ece Güngüney](https://github.com/eecegunguney) | [Frankl.ai](https://github.com/eecegunguney/Frankl.ai) | Python, Ollama | Frankl.ai, local bir LLM üzerinde çalışan, logoterapi ve BDT teknikleriyle kullanıcıların anlam arayışına ve duygu durumlarına rehberlik eden güvenli bir yapay zekâ sohbet arkadaşıdır. |
| 12 | [Doğa Güneş](https://github.com/doagunes) | [csv-analyst-agent](https://github.com/doagunes/csv-analyst-agent) | Python, Ollama | CSV verisiyle doğal dilde konuşan, tamamen yerel (Ollama + llama3.1) çalışan analiz agent'ı. |
| 13 | [Berna Talay](https://github.com/bernatalayy) | [email-classification-agent](https://github.com/bernatalayy/email-classification-agent) | Python, Ollama | Müşteri e-postalarını analiz eden, özetleyen, ticket oluşturan, öneri yanıtları üreten ve ticket kayıtlarını Excel’de saklayan AI agent. |
| 14 | [Seden Özcan](https://github.com/sednozcan) | [ResearchPilot](https://github.com/sednozcan/research-pilot) | Python, FastAPI, React, Gemini API | Kullanıcı sorusunu analiz ederek araştırma planı oluşturan ve Gemini API ile yapılandırılmış araştırma raporu üreten AI agent. |
| 15 | [Gamze Çakan](https://github.com/gamzecakan) | [study-planner-agent](https://github.com/gamzecakan/study-planner-agent) | Python, LangChain, Groq | An AI study planner that collects user information, asks for missing details, and generates personalized study plans using a Large Language Model. |
| 16 | [Beyza Nur Tiril](https://github.com/beyzanurtiril) | [makeup-agent](https://github.com/beyzanurtiril/makeup-agent) | Python, Gemini API, Tavily | An agent that recommends cool-toned makeup products by category (lipstick, eyeshadow, concealer, etc.) using real-time web search. |
| 17 | [Doğa İpek](https://github.com/dogaaipek) | [smart-study-planner-agent](https://github.com/dogaaipek/smart-study-planner-agent) | Python, Rule-based Agent, Optional LLM | A category-based study planner agent that detects missing inputs and generates personalized plans with mini quiz support. |
| 18 | [Cansu Cebesoy](https://github.com/cansucebesoy)  | [customer-support-agent](https://github.com/cansucebesoy/customer-support-agent)| Java, Google Gemini API, Resend | A Java console application that analyzes and automatically classifies customer messages using Gemini AI, and sends a confirmation email to the customer via the Resend API. |

## Kendini Ekle

Ödevini tamamladıysan listeye eklenmek için bir Pull Request aç:

1. Bu repoyu fork'la.
2. `odevler.md` dosyasındaki tabloya aşağıdaki şablonu doldurup **en alta** yeni satır olarak ekle(PR merge sırasına göre numara olacağı için, en başına numara eklemene gerek yok)
3. PR aç — kısa bir açıklama yeterli.

```markdown
| NULL | [Ad Soyad](https://github.com/kullanici-adi) | [repo-adi](https://github.com/kullanici-adi/repo-adi) | Dil, Framework | Agent'ının ne yaptığını anlatan tek cümle. |
```

PR açmak da bu ödevin doğal bir parçası — GitHub üzerinde katkı akışını denemek için güzel bir fırsat.
