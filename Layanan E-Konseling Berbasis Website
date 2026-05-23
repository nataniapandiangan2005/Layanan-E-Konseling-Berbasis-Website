export default function EKonselingWebsite() {
  const steps = [
    {
      number: "1",
      title: "Masuk",
      color: "bg-blue-500",
      desc: "Pengguna mengakses website e-konseling melalui perangkat yang tersedia.",
      items: ["Akses website", "Login / Registrasi", "Pilih menu e-konseling"],
    },
    {
      number: "2",
      title: "Daftar",
      color: "bg-green-500",
      desc: "Pengguna mengisi data diri dan memilih jadwal konseling.",
      items: ["Isi formulir", "Pilih konselor", "Pilih jadwal", "Kirim permohonan"],
    },
    {
      number: "3",
      title: "Konseling",
      color: "bg-orange-500",
      desc: "Konselor melakukan layanan konseling secara online.",
      items: ["Terima jadwal", "Chat / Video Call", "Catat hasil", "Rekomendasi lanjutan"],
    },
    {
      number: "4",
      title: "Selesai",
      color: "bg-purple-500",
      desc: "Data tersimpan dan admin membuat evaluasi layanan.",
      items: ["Data tersimpan", "Laporan layanan", "Evaluasi pengguna"],
    },
  ];

  const teams = [
    {
      title: "Admin",
      color: "text-blue-600",
      names: ["Khusnul Uswatun Hasanah"],
    },
    {
      title: "Konselor",
      color: "text-green-600",
      names: ["Sulis Apriani", "Rosa Arsela"],
    },
    {
      title: "Content Creator",
      color: "text-pink-500",
      names: ["Natania Pandiangan", "Suci Lestari"],
    },
  ];

  const benefits = [
    "Mudah diakses kapan saja dan di mana saja",
    "Nyaman, aman, dan terpercaya",
    "Fleksibel sesuai kebutuhan",
    "Mendukung kesehatan mental dan perkembangan diri",
  ];

  return (
    <div className="min-h-screen bg-gradient-to-br from-purple-50 via-white to-pink-50 text-gray-800">
      {/* Hero Section */}
      <section className="relative overflow-hidden">
        <div className="absolute top-0 left-0 w-72 h-72 bg-purple-200 rounded-full blur-3xl opacity-40"></div>
        <div className="absolute bottom-0 right-0 w-72 h-72 bg-pink-200 rounded-full blur-3xl opacity-40"></div>

        <div className="relative max-w-7xl mx-auto px-6 py-16 grid lg:grid-cols-2 gap-10 items-center">
          <div>
            <span className="inline-block bg-purple-100 text-purple-700 px-4 py-2 rounded-full text-sm font-semibold mb-4">
              Layanan Konseling Digital
            </span>

            <h1 className="text-5xl lg:text-6xl font-extrabold leading-tight mb-6">
              LAYANAN <span className="text-cyan-500">E-KONSELING</span>
              <br />
              <span className="text-pink-500">Berbasis Website</span>
            </h1>

            <p className="text-lg text-gray-600 mb-8 leading-relaxed">
              Platform layanan konseling online yang memudahkan pengguna untuk mendapatkan bantuan, konsultasi, dan dukungan secara aman, fleksibel, dan profesional.
            </p>

            <div className="flex flex-wrap gap-4">
              <button className="bg-gradient-to-r from-cyan-500 to-blue-600 text-white px-6 py-3 rounded-2xl font-semibold shadow-lg hover:scale-105 transition">
                Mulai Konseling
              </button>
              <button className="border-2 border-purple-300 text-purple-700 px-6 py-3 rounded-2xl font-semibold hover:bg-purple-50 transition">
                Pelajari Layanan
              </button>
            </div>
          </div>

          <div className="bg-white rounded-[30px] p-8 shadow-2xl border border-purple-100">
            <div className="grid grid-cols-2 gap-4">
              <div className="bg-blue-50 p-5 rounded-2xl">
                <div className="text-4xl mb-3">💻</div>
                <h3 className="font-bold text-blue-700">Online</h3>
                <p className="text-sm text-gray-600 mt-2">Konseling dapat dilakukan dari mana saja.</p>
              </div>

              <div className="bg-pink-50 p-5 rounded-2xl">
                <div className="text-4xl mb-3">🔒</div>
                <h3 className="font-bold text-pink-600">Rahasia</h3>
                <p className="text-sm text-gray-600 mt-2">Data dan privasi pengguna terlindungi.</p>
              </div>

              <div className="bg-green-50 p-5 rounded-2xl">
                <div className="text-4xl mb-3">📅</div>
                <h3 className="font-bold text-green-600">Fleksibel</h3>
                <p className="text-sm text-gray-600 mt-2">Atur jadwal sesuai kebutuhan pengguna.</p>
              </div>

              <div className="bg-purple-50 p-5 rounded-2xl">
                <div className="text-4xl mb-3">🤝</div>
                <h3 className="font-bold text-purple-600">Profesional</h3>
                <p className="text-sm text-gray-600 mt-2">Didampingi konselor yang kompeten.</p>
              </div>
            </div>
          </div>
        </div>
      </section>

      {/* Alur Layanan */}
      <section className="max-w-7xl mx-auto px-6 py-16">
        <div className="text-center mb-12">
          <h2 className="text-4xl font-extrabold text-gray-800 mb-4">
            Alur Layanan E-Konseling
          </h2>
          <p className="text-gray-600 text-lg">
            Proses layanan yang mudah, cepat, dan terstruktur.
          </p>
        </div>

        <div className="grid md:grid-cols-2 xl:grid-cols-4 gap-6">
          {steps.map((step) => (
            <div
              key={step.number}
              className="bg-white rounded-[28px] p-6 shadow-xl border border-gray-100 hover:-translate-y-2 transition duration-300"
            >
              <div className={`${step.color} text-white w-14 h-14 flex items-center justify-center rounded-2xl text-2xl font-bold mb-5`}>
                {step.number}
              </div>

              <h3 className="text-2xl font-bold mb-3">{step.title}</h3>
              <p className="text-gray-600 mb-5 text-sm leading-relaxed">
                {step.desc}
              </p>

              <div className="space-y-3">
                {step.items.map((item, index) => (
                  <div
                    key={index}
                    className="bg-gray-50 rounded-xl px-4 py-3 text-sm font-medium border border-gray-100"
                  >
                    {item}
                  </div>
                ))}
              </div>
            </div>
          ))}
        </div>
      </section>

      {/* Tim Layanan */}
      <section className="bg-gradient-to-r from-cyan-500 to-blue-600 py-16 px-6">
        <div className="max-w-6xl mx-auto">
          <div className="text-center text-white mb-12">
            <h2 className="text-4xl font-extrabold mb-4">Tim Layanan</h2>
            <p className="text-lg opacity-90">
              Tim profesional yang mendukung layanan e-konseling.
            </p>
          </div>

          <div className="grid md:grid-cols-3 gap-6">
            {teams.map((team, index) => (
              <div
                key={index}
                className="bg-white rounded-[28px] p-8 shadow-2xl"
              >
                <div className="w-20 h-20 bg-gradient-to-br from-purple-200 to-pink-200 rounded-full flex items-center justify-center text-3xl mb-5">
                  👩
                </div>

                <h3 className={`text-2xl font-bold mb-4 ${team.color}`}>
                  {team.title}
                </h3>

                <div className="space-y-2">
                  {team.names.map((name, i) => (
                    <div
                      key={i}
                      className="bg-gray-50 px-4 py-3 rounded-xl border border-gray-100"
                    >
                      {name}
                    </div>
                  ))}
                </div>
              </div>
            ))}
          </div>
        </div>
      </section>

      {/* Ketentuan */}
      <section className="max-w-7xl mx-auto px-6 py-16">
        <div className="bg-white rounded-[32px] shadow-2xl p-10 border border-purple-100">
          <div className="grid lg:grid-cols-2 gap-10 items-center">
            <div>
              <h2 className="text-4xl font-extrabold mb-6 text-purple-700">
                Ketentuan Layanan
              </h2>

              <div className="space-y-4">
                {[
                  "Layanan e-konseling bersifat rahasia.",
                  "Pengguna wajib menggunakan bahasa yang sopan dan santun.",
                  "Konselor menjaga profesionalitas dan etika layanan.",
                  "Layanan dapat diakses melalui smartphone maupun komputer.",
                  "Layanan tersedia secara sinkronous dan asinkronous.",
                ].map((rule, i) => (
                  <div
                    key={i}
                    className="flex items-start gap-4 bg-purple-50 rounded-2xl p-4"
                  >
                    <div className="w-10 h-10 rounded-full bg-purple-600 text-white flex items-center justify-center font-bold">
                      ✓
                    </div>
                    <p className="text-gray-700 leading-relaxed">{rule}</p>
                  </div>
                ))}
              </div>
            </div>

            <div className="bg-gradient-to-br from-purple-500 to-pink-500 rounded-[30px] p-10 text-white shadow-xl">
              <h3 className="text-3xl font-bold mb-6">
                Dukungan Kesehatan Mental Digital
              </h3>

              <p className="leading-relaxed text-lg mb-8 opacity-95">
                Website e-konseling membantu pengguna memperoleh layanan konseling dengan lebih mudah, nyaman, dan aman tanpa batasan tempat dan waktu.
              </p>

              <div className="grid grid-cols-2 gap-4">
                <div className="bg-white/20 backdrop-blur-sm rounded-2xl p-5">
                  <div className="text-3xl mb-2">💬</div>
                  <p className="font-semibold">Chat Konseling</p>
                </div>

                <div className="bg-white/20 backdrop-blur-sm rounded-2xl p-5">
                  <div className="text-3xl mb-2">📹</div>
                  <p className="font-semibold">Video Call</p>
                </div>

                <div className="bg-white/20 backdrop-blur-sm rounded-2xl p-5">
                  <div className="text-3xl mb-2">📊</div>
                  <p className="font-semibold">Evaluasi</p>
                </div>

                <div className="bg-white/20 backdrop-blur-sm rounded-2xl p-5">
                  <div className="text-3xl mb-2">🔐</div>
                  <p className="font-semibold">Keamanan Data</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      {/* Manfaat */}
      <section className="py-16 bg-gradient-to-br from-pink-50 via-white to-cyan-50 px-6">
        <div className="max-w-6xl mx-auto text-center">
          <h2 className="text-4xl font-extrabold mb-4">
            Manfaat Layanan E-Konseling
          </h2>

          <p className="text-gray-600 text-lg mb-12">
            Memberikan pengalaman konseling yang lebih efektif dan modern.
          </p>

          <div className="grid md:grid-cols-2 lg:grid-cols-4 gap-6">
            {benefits.map((benefit, index) => (
              <div
                key={index}
                className="bg-white rounded-[28px] p-8 shadow-lg border border-gray-100 hover:shadow-2xl transition"
              >
                <div className="text-5xl mb-4">
                  {index === 0
                    ? "🌍"
                    : index === 1
                    ? "🛡️"
                    : index === 2
                    ? "⏰"
                    : "❤️"}
                </div>

                <p className="font-semibold text-gray-700 leading-relaxed">
                  {benefit}
                </p>
              </div>
            ))}
          </div>
        </div>
      </section>

      {/* Footer */}
      <footer className="bg-gradient-to-r from-purple-700 to-pink-600 text-white py-8 px-6 text-center">
        <h3 className="text-2xl font-bold mb-3">E-Konseling Berbasis Website</h3>
        <p className="max-w-3xl mx-auto opacity-90 leading-relaxed">
          Semua data dan informasi pengguna dilindungi oleh sistem keamanan dan hanya digunakan untuk kepentingan layanan konseling.
        </p>

        <div className="mt-6 text-sm opacity-80">
          © 2026 Layanan E-Konseling | Website Konseling Digital
        </div>
      </footer>
    </div>
  );
}
