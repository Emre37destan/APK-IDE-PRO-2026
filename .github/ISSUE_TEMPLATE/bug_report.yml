name: 🐛 Bug Report / Hata Bildirimi

description: Uygulamada bir hata buldum. / I found a bug in the application.

title: "[BUG] "
labels: ["bug", "needs-triage"]

body:
  - type: markdown
    attributes:
      value: |
        Hata bildirdiğiniz için teşekkür ederiz! / Thank you for reporting a bug!
        Lütfen aşağıdaki bilgileri sağlayınız. / Please provide the following information.

  - type: dropdown
    id: os
    attributes:
      label: "🖥️ İşletim Sistemi / Operating System"
      options:
        - Windows 11
        - Windows 10
        - Ubuntu 22.04
        - Ubuntu 20.04
        - macOS (Not Supported)
        - Diğer / Other
    validations:
      required: true

  - type: input
    id: python_version
    attributes:
      label: "🐍 Python Sürümü / Python Version"
      placeholder: "e.g., 3.10.5"
      description: "İlgili python versiyonunu yazınız. / Write your Python version."
    validations:
      required: true

  - type: input
    id: java_version
    attributes:
      label: "☕ Java Sürümü / Java Version"
      placeholder: "e.g., openjdk-11-jdk"
      description: "Java version (eğer varsa) / Java version if applicable"
    validations:
      required: false

  - type: textarea
    id: bug_description
    attributes:
      label: "📝 Hata Açıklaması / Bug Description"
      description: "Hata hakkında detaylı bir açıklama yapınız."
      placeholder: "Hata ne ve nasıl oluşuyor? / What is the bug and how does it occur?"
    validations:
      required: true

  - type: textarea
    id: reproduce_steps
    attributes:
      label: "🔄 Tekrar Adımları / Steps to Reproduce"
      description: "Hatayı tekrar tetiklemek için adımları yazınız."
      placeholder: |
        1. Adım / Step
        2. Adım / Step
        3. Hatanın oluştuğu nokta / Error occurs
    validations:
      required: true

  - type: textarea
    id: expected_behavior
    attributes:
      label: "✅ Beklenen Davranış / Expected Behavior"
      placeholder: "Normal koşullarda ne olması gerekirdi? / What should happen normally?"
    validations:
      required: true

  - type: textarea
    id: actual_behavior
    attributes:
      label: "❌ Gerçek Davranış / Actual Behavior"
      placeholder: "Aslında ne oldu? / What actually happened?"
    validations:
      required: true

  - type: textarea
    id: error_log
    attributes:
      label: "📋 Hata Günlüğü / Error Log"
      description: "Terminal veya log dosyasından hatayı kopyalayın."
      placeholder: |
        ```
        Traceback (most recent call last):
          ...
        ```
      render: shell
    validations:
      required: false

  - type: textarea
    id: screenshot
    attributes:
      label: "📸 Ekran Görüntüsü / Screenshot"
      description: "Varsa ekran görüntüsü ekleyebilirsiniz."
      placeholder: "(Drag files here)"
    validations:
      required: false

  - type: checkboxes
    id: checklist
    attributes:
      label: "📋 Kontrol Listesi / Checklist"
      options:
        - label: "Benzer bir issue daha önce açılmış mı kontrol ettim / I've searched for similar issues"
          required: true
        - label: "En son sürümü kullanıyor muyum kontrol ettim / I'm using the latest version"
          required: true
        - label: "Tüm gerekli bilgileri sağladım / I've provided all required information"
          required: true
