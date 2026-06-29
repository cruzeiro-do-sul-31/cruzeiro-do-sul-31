export default function MemorialLojaMaconica() {
  const menu = [
    "História",
    "Veneráveis",
    "Galeria",
    "Painel",
    "Contato",
  ];
  const veneraveis = [
  { nome: "Eli Dutra", periodo: "1971/1972 – 1972/1973 – 1973/1974", foto: "https://via.placeholder.com/600x800?text=Eli+Dutra" },
  { nome: "Benedito Celestino de Barros", periodo: "1974/1975 – 1975/1976", foto: "https://via.placeholder.com/600x800?text=Benedito+Celestino" },
  { nome: "Antônio Gomes de Almeida", periodo: "1976/1977 – 1978/1979 – 1979/1980 – 1980/1981 – 1982/1983 – 1983/1984 – 1984/1985", foto: "https://via.placeholder.com/600x800?text=Antonio+Gomes" },
  { nome: "Antônio de Castela", periodo: "1977/1978", foto: "https://via.placeholder.com/600x800?text=Antonio+de+Castela" },
  { nome: "Dalmo Marques da Fonseca", periodo: "1981/1982", foto: "https://via.placeholder.com/600x800?text=Dalmo+Marques" },
  { nome: "Joel Alves Pinto", periodo: "1985/1986", foto: "https://via.placeholder.com/600x800?text=Joel+Alves" },
  { nome: "Nelson Gonçalves Correlo", periodo: "1986/1987 – 1987/1988 – 1999/2000", foto: "https://via.placeholder.com/600x800?text=Nelson+Correlo" },
  { nome: "Joanyr Alves Pinto", periodo: "1988/1989", foto: "https://via.placeholder.com/600x800?text=Joanyr+Alves" },
  { nome: "Marcelo de Amorim Boaventura", periodo: "1989/1990", foto: "https://via.placeholder.com/600x800?text=Marcelo+Boaventura" },
  { nome: "Roberto Deny Bandeira de Melo", periodo: "1990/1991", foto: "https://via.placeholder.com/600x800?text=Roberto+Deny" },
  { nome: "Carlos Camargo", periodo: "1991/1992", foto: "https://via.placeholder.com/600x800?text=Carlos+Camargo" },
  { nome: "Jorge Luiz Monteiro Freitas", periodo: "1992/1993", foto: "https://via.placeholder.com/600x800?text=Jorge+Freitas" },
  { nome: "Sebastião Santos", periodo: "1993/1994", foto: "https://via.placeholder.com/600x800?text=Sebastiao+Santos" },
  { nome: "Antônio Henrique de Oliveira", periodo: "1994/1995", foto: "https://via.placeholder.com/600x800?text=Antonio+Henrique" },
  { nome: "Dimar Correa", periodo: "1995/1996", foto: "https://via.placeholder.com/600x800?text=Dimar+Correa" },
  { nome: "José Carlos Matheus Fava", periodo: "1996/1997", foto: "https://via.placeholder.com/600x800?text=Jose+Fava" },
  { nome: "Martinho Nelson da Silva Santos", periodo: "1997/1998", foto: "https://via.placeholder.com/600x800?text=Martinho+Nelson" },
  { nome: "Aristides dos Santos", periodo: "1998/1999", foto: "https://via.placeholder.com/600x800?text=Aristides+dos+Santos" },
  { nome: "Haroldo Marques da Silveira", periodo: "2001/2002", foto: "https://via.placeholder.com/600x800?text=Haroldo+Silveira" },
  { nome: "Nelson Levi Ramos", periodo: "2002/2003", foto: "https://via.placeholder.com/600x800?text=Nelson+Levi" },
  { nome: "Jorge Mendelzon dos S. Macieira", periodo: "2003/2004", foto: "https://via.placeholder.com/600x800?text=Jorge+Mendelzon" },
  { nome: "Francisco Jadson Miranda Viana", periodo: "2004/2005 – 2015/2016", foto: "https://via.placeholder.com/600x800?text=Francisco+Jadson" },
  { nome: "Edson Luiz Duarte Simonato", periodo: "2005/2006", foto: "https://via.placeholder.com/600x800?text=Edson+Simonato" },
  { nome: "Robson da Silva Barbosa", periodo: "2006/2007", foto: "https://via.placeholder.com/600x800?text=Robson+Barbosa" },
  { nome: "José da Rosa Mesquita", periodo: "2007/2008", foto: "https://via.placeholder.com/600x800?text=Jose+Mesquita" },
  { nome: "Paulo Marcos de Brito", periodo: "2008/2009 – 2011/2012", foto: "https://via.placeholder.com/600x800?text=Paulo+Marcos" },
  { nome: "Bruno Cesar de Souza", periodo: "2009/2010", foto: "https://via.placeholder.com/600x800?text=Bruno+Cesar" },
  { nome: "Edson Pinto da Rocha", periodo: "2010/2011", foto: "https://via.placeholder.com/600x800?text=Edson+Rocha" },
  { nome: "Rogério de Souza Vigné", periodo: "2012/2013", foto: "https://via.placeholder.com/600x800?text=Rogerio+Vigne" },
  { nome: "José Fontenele Filho", periodo: "2013/2014 – 2014/2015", foto: "https://via.placeholder.com/600x800?text=Jose+Fontenele" },
  { nome: "Deivide de Paula Dias", periodo: "2016/2017 – 2020/2021", foto: "https://via.placeholder.com/600x800?text=Deivide+Dias" },
  { nome: "Hiram da Costa Araújo Filho", periodo: "2017/2018", foto: "https://via.placeholder.com/600x800?text=Hiram+Araujo" },
  { nome: "Paulo Roberto Vendramin", periodo: "2018/2019", foto: "https://via.placeholder.com/600x800?text=Paulo+Vendramin" },
  { nome: "Luiz Pimenta Monteiro", periodo: "2019/2020", foto: "https://via.placeholder.com/600x800?text=Luiz+Pimenta" },
  { nome: "Jupiratan de Oliveira Fagundes", periodo: "2021/2022 – 2022/2023", foto: "https://via.placeholder.com/600x800?text=Jupiratan" },
  { nome: "Moises Baptista Barbosa", periodo: "2023/2024", foto: "https://via.placeholder.com/600x800?text=Moises+Barbosa" },
  { nome: "Cláudio Nogueira Nunes", periodo: "2024/2025", foto: "https://via.placeholder.com/600x800?text=Claudio+Nunes" },
  { nome: "Igor Dias da Silva", periodo: "2025/2026", foto: "https://via.placeholder.com/600x800?text=Igor+Dias" },
];

  const galeria = [
    "https://images.unsplash.com/photo-1517457373958-b7bdd4587205?q=80&w=1200&auto=format&fit=crop",
    "https://images.unsplash.com/photo-1516321318423-f06f85e504b3?q=80&w=1200&auto=format&fit=crop",
    "https://images.unsplash.com/photo-1511578314322-379afb476865?q=80&w=1200&auto=format&fit=crop",
    "https://images.unsplash.com/photo-1528605248644-14dd04022da1?q=80&w=1200&auto=format&fit=crop",
  ];

  return (
    <div className="bg-black text-white font-sans overflow-x-hidden">
      {/* HEADER */}
      <header className="fixed top-0 left-0 right-0 z-50 bg-black/80 backdrop-blur-md border-b border-yellow-500/10">
        <div className="max-w-7xl mx-auto flex items-center justify-between px-6 py-4">
          <div className="flex items-center gap-4">
            <img
              src="/brasao-loja.png"
              alt="Brasão"
              className="w-14"
            />

            <div>
              <h1 className="text-yellow-400 font-bold text-lg leading-none">
                Cruzeiro do Sul Nº 31
              </h1>
              <p className="text-xs text-gray-400 mt-1">
                Memorial Digital Oficial
              </p>
            </div>
          </div>

          <nav className="hidden md:flex gap-8 text-sm text-gray-300">
            {menu.map((item, index) => (
              <a
                key={index}
                href="#"
                className="hover:text-yellow-400 transition"
              >
                {item}
              </a>
            ))}
          </nav>
        </div>
      </header>

      <div className="pt-24">
    <div className="min-h-screen bg-black text-white font-sans">
      {/* HERO */}
      <section className="relative h-[90vh] flex items-center justify-center overflow-hidden">
        <img
          src="https://images.unsplash.com/photo-1511818966892-d7d671e672a2?q=80&w=1600&auto=format&fit=crop"
          alt="Templo"
          className="absolute inset-0 w-full h-full object-cover opacity-30"
        />

        <div className="relative z-10 text-center px-6 max-w-4xl">
          <div className="mb-8 flex justify-center">
            <img
              src="/brasao-loja.png"
              alt="Brasão da Loja"
              className="w-64 md:w-80 drop-shadow-2xl"
            />
          </div>

          <h1 className="text-5xl md:text-7xl font-bold text-yellow-400 mb-6">
            Memorial Digital
          </h1>

          <h2 className="text-2xl md:text-4xl font-light mb-8">
            Loja Maçônica Cruzeiro do Sul
          </h2>

          <p className="text-lg text-gray-300 leading-relaxed max-w-3xl mx-auto">
            Um espaço dedicado à preservação da história, memória e legado dos
            irmãos que ajudaram a construir nossa trajetória.
          </p>

          <div className="mt-10 flex flex-wrap gap-4 justify-center">
            <a
              href="#historia"
              className="bg-yellow-500 hover:bg-yellow-400 text-black px-6 py-3 rounded-2xl font-semibold transition"
            >
              Conheça Nossa História
            </a>

            <a
              href="#galeria"
              className="border border-yellow-500 text-yellow-400 hover:bg-yellow-500 hover:text-black px-6 py-3 rounded-2xl font-semibold transition"
            >
              Ver Galeria
            </a>
          </div>
        </div>
      </section>

      {/* HISTORIA */}
      <section id="historia" className="py-24 px-6 bg-zinc-950">
        <div className="max-w-6xl mx-auto grid md:grid-cols-2 gap-16 items-center">
          <div>
            <h2 className="text-4xl font-bold text-yellow-400 mb-8">
              História da Loja
            </h2>

            <p className="text-gray-300 leading-8 mb-6">
              Fundada com os princípios de fraternidade, moralidade e evolução
              humana, nossa Loja tornou-se referência na formação de homens
              comprometidos com o bem comum, a justiça e a caridade.
            </p>

            <p className="text-gray-300 leading-8 mb-6">
              Ao longo dos anos, diversas gestões contribuíram para o
              fortalecimento da instituição, promovendo ações sociais,
              desenvolvimento intelectual e união entre os irmãos.
            </p>

            <div className="grid grid-cols-2 gap-4 mt-10">
              <div className="bg-black border border-yellow-500/30 rounded-2xl p-6">
                <h3 className="text-3xl font-bold text-yellow-400">1958</h3>
                <p className="text-gray-400 mt-2">Ano de Fundação</p>
              </div>

              <div className="bg-black border border-yellow-500/30 rounded-2xl p-6">
                <h3 className="text-3xl font-bold text-yellow-400">68+</h3>
                <p className="text-gray-400 mt-2">Anos de História</p>
              </div>
            </div>
          </div>

          <div>
            <img
              src="https://images.unsplash.com/photo-1517048676732-d65bc937f952?q=80&w=1400&auto=format&fit=crop"
              alt="Loja"
              className="rounded-3xl shadow-2xl border border-yellow-500/20"
            />
          </div>
        </div>
      </section>

      {/* VENERAVEIS */}
      <section className="py-24 px-6 bg-black">
        <div className="max-w-7xl mx-auto">
          <div className="text-center mb-16">
            <h2 className="text-4xl font-bold text-yellow-400 mb-4">
              Painel de Veneráveis
            </h2>
            <p className="text-gray-400 max-w-2xl mx-auto">
              Honramos os irmãos que conduziram nossa Loja com sabedoria,
              dedicação e espírito fraternal.
            </p>
          </div>

          <div className="grid md:grid-cols-3 gap-8">
            {veneraveis.map((item, index) => (
              <div
                key={index}
                className="bg-zinc-950 border border-yellow-500/20 rounded-3xl overflow-hidden hover:scale-105 transition duration-300"
              >
                <img
                  src={item.foto}
                  alt={item.nome}
                  className="w-full h-80 object-cover"
                />

                <div className="p-6 text-center">
                  <h3 className="text-2xl font-semibold text-yellow-400">
                    {item.nome}
                  </h3>

                  <p className="text-gray-400 mt-2">Gestão {item.periodo}</p>
                </div>
              </div>
            ))}
          </div>
        </div>
      </section>

      {/* CONSTRUCAO */}
      <section className="py-24 px-6 bg-zinc-950">
        <div className="max-w-6xl mx-auto">
          <div className="text-center mb-16">
            <h2 className="text-4xl font-bold text-yellow-400 mb-4">
              Construção do Painel
            </h2>

            <p className="text-gray-400 max-w-3xl mx-auto leading-8">
              Esta seção registra todo o processo de criação do painel físico de
              veneráveis, preservando a memória da dedicação e do trabalho
              realizado pelos irmãos envolvidos no projeto.
            </p>
          </div>

          <div className="grid md:grid-cols-3 gap-8">
            <div className="bg-black rounded-3xl p-8 border border-yellow-500/20">
              <h3 className="text-2xl text-yellow-400 font-semibold mb-4">
                Planejamento
              </h3>

              <p className="text-gray-400 leading-7">
                Desenvolvimento do conceito, escolha dos materiais e definição
                do design do painel.
              </p>
            </div>

            <div className="bg-black rounded-3xl p-8 border border-yellow-500/20">
              <h3 className="text-2xl text-yellow-400 font-semibold mb-4">
                Execução
              </h3>

              <p className="text-gray-400 leading-7">
                Registro fotográfico da fabricação, montagem e acabamento da
                estrutura.
              </p>
            </div>

            <div className="bg-black rounded-3xl p-8 border border-yellow-500/20">
              <h3 className="text-2xl text-yellow-400 font-semibold mb-4">
                Instalação
              </h3>

              <p className="text-gray-400 leading-7">
                Fotos e informações da instalação final do painel dentro da
                Loja.
              </p>
            </div>
          </div>
        </div>
      </section>

      {/* GALERIA */}
      <section id="galeria" className="py-24 px-6 bg-black">
        <div className="max-w-7xl mx-auto">
          <div className="text-center mb-16">
            <h2 className="text-4xl font-bold text-yellow-400 mb-4">
              Galeria Histórica
            </h2>

            <p className="text-gray-400">
              Eventos, sessões, homenagens e momentos históricos da Loja.
            </p>
          </div>

          <div className="grid md:grid-cols-2 lg:grid-cols-4 gap-6">
            {galeria.map((foto, index) => (
              <div
                key={index}
                className="overflow-hidden rounded-3xl border border-yellow-500/20"
              >
                <img
                  src={foto}
                  alt="Galeria"
                  className="w-full h-72 object-cover hover:scale-110 transition duration-500"
                />
              </div>
            ))}
          </div>
        </div>
      </section>

      {/* QR CODE */}
      <section className="py-24 px-6 bg-zinc-950">
        <div className="max-w-4xl mx-auto text-center">
          <h2 className="text-4xl font-bold text-yellow-400 mb-6">
            Acesse pelo QR Code
          </h2>

          <p className="text-gray-400 leading-8 mb-10 max-w-2xl mx-auto">
            Disponibilize este QR Code na entrada da Loja, próximo ao painel de
            veneráveis ou em materiais institucionais para que visitantes possam
            acessar o memorial digital.
          </p>

          <div className="flex justify-center">
            <img
              src="https://api.qrserver.com/v1/create-qr-code/?size=300x300&data=https://memorial-loja.vercel.app"
              alt="QR Code"
              className="bg-white p-4 rounded-3xl"
            />
          </div>

          <p className="text-yellow-400 mt-6 break-all">
            https://memorial-loja.vercel.app
          </p>
        </div>
      </section>

      {/* FOOTER */}
      <footer className="bg-black border-t border-yellow-500/10 py-16 px-6 text-center">
        <div className="flex justify-center mb-6">
          <img
            src="/brasao-loja.png"
            alt="Brasão"
            className="w-32 opacity-90"
          />
        </div>

        <p className="text-gray-500 text-lg">
          Memorial Digital • Loja Maçônica Cruzeiro do Sul Nº 31
        </p>

        <p className="text-gray-600 text-sm mt-2">
          Preservando nossa história para as futuras gerações.
        </p>
      </footer>

      {/* CTA FINAL */}}
      <section className="relative py-32 px-6 bg-gradient-to-b from-black to-zinc-950 overflow-hidden">
        <div className="absolute inset-0 opacity-10">
          <img
            src="/brasao-loja.png"
            alt="Fundo"
            className="w-[700px] mx-auto mt-10"
          />
        </div>

        <div className="relative z-10 max-w-5xl mx-auto text-center">
          <h2 className="text-5xl font-bold text-yellow-400 mb-8">
            Preservando Nossa História
          </h2>

          <p className="text-xl text-gray-300 leading-9 max-w-3xl mx-auto mb-12">
            Este memorial digital foi criado para eternizar a trajetória dos
            irmãos, registrar momentos históricos e preservar o legado da
            Augusta, Respeitável, Fiel e Grande Benemérita Loja Maçônica
            Cruzeiro do Sul Nº 31.
          </p>

          <div className="flex flex-wrap justify-center gap-6">
            <button className="bg-yellow-500 hover:bg-yellow-400 text-black font-semibold px-8 py-4 rounded-2xl transition duration-300 shadow-2xl">
              Explorar Memorial
            </button>

            <button className="border border-yellow-500 text-yellow-400 hover:bg-yellow-500 hover:text-black px-8 py-4 rounded-2xl transition duration-300">
              Ver Galeria Histórica
            </button>
          </div>
        </div>
      </section>

      {/* FOOTER PREMIUM */}
      <footer className="bg-black border-t border-yellow-500/10 py-20 px-6">
        <div className="max-w-7xl mx-auto grid md:grid-cols-3 gap-12 items-start">
          <div>
            <img
              src="/brasao-loja.png"
              alt="Brasão"
              className="w-32 mb-6"
            />

            <p className="text-gray-400 leading-8">
              Memorial digital dedicado à preservação da memória e da história
              da Loja Maçônica Cruzeiro do Sul Nº 31.
            </p>
          </div>

          <div>
            <h3 className="text-yellow-400 text-xl font-semibold mb-6">
              Navegação
            </h3>

            <ul className="space-y-4 text-gray-400">
              <li>História da Loja</li>
              <li>Painel de Veneráveis</li>
              <li>Galeria Histórica</li>
              <li>Construção do Painel</li>
            </ul>
          </div>

          <div>
            <h3 className="text-yellow-400 text-xl font-semibold mb-6">
              Acesso Rápido
            </h3>

            <div className="bg-white inline-block p-4 rounded-2xl">
              <img
                src="https://api.qrserver.com/v1/create-qr-code/?size=220x220&data=https://memorial-loja.vercel.app"
                alt="QR Code"
                className="w-44"
              />
            </div>
          </div>
        </div>

        <div className="border-t border-yellow-500/10 mt-16 pt-8 text-center text-gray-600 text-sm">
          © 2026 Loja Maçônica Cruzeiro do Sul Nº 31 • Todos os direitos reservados.
        </div>
      </footer>
    </div>
  );
}
