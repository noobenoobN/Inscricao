<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tela Usada - Controle de Serigrafia</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-900 text-gray-100 font-sans min-h-screen relative">

  <header class="bg-gray-800 border-b border-gray-700 p-4 shadow-md">
    <div class="max-w-7xl mx-auto flex justify-between items-center">
      <h1 class="text-2xl font-bold tracking-wider text-emerald-400">TELA USADA</h1>
      <div class="flex items-center gap-3">
        <input type="file" id="input-importar" accept=".txt" class="hidden">
        
        <button onclick="document.getElementById('input-importar').click()" class="bg-gray-700 hover:bg-gray-650 text-emerald-400 text-sm font-semibold py-1.5 px-4 rounded border border-gray-600 transition">
          Importar (.TXT)
        </button>
        
        <button id="btn-exportar" class="bg-gray-700 hover:bg-gray-600 text-gray-250 text-sm font-semibold py-1.5 px-4 rounded border border-gray-600 transition">
          Baixar Tudo (.TXT)
        </button>
        
        <!-- Clique para abrir o Painel Operacional -->
        <span onclick="abrirModalOnline()" class="text-sm bg-gray-700 px-3 py-1 rounded-full text-gray-300 flex items-center gap-2 cursor-pointer hover:bg-gray-650 transition" title="Clique para abrir o Painel Operacional">
          <span class="w-2 h-2 rounded-full bg-emerald-500 animate-pulse"></span>
          Painel Operacional (<span id="count-online">1</span>)
        </span>
      </div>
    </div>
  </header>

  <main class="max-w-7xl mx-auto p-4 md:p-6 space-y-6">

    <section class="bg-gray-800 border border-gray-700 rounded-lg p-5 shadow-lg">
      <h2 class="text-lg font-semibold mb-4 text-gray-200">Cadastrar Nova Ordem / Tela</h2>
      <form id="form-tela" class="grid grid-cols-1 md:grid-cols-3 gap-4 items-end">
        
        <div>
          <label class="block text-sm font-medium text-gray-400 mb-1">Número da O.S.</label>
          <input type="number" id="input-os" required class="w-full bg-gray-700 border border-gray-600 rounded p-2.5 text-white focus:outline-none focus:border-emerald-500" placeholder="Ex: 1042">
        </div>

        <div>
          <label class="block text-sm font-medium text-gray-400 mb-1">Lineatura da Tela (Fios)</label>
          <select id="select-linhagem" required class="w-full bg-gray-700 border border-gray-600 rounded p-2.5 text-white focus:outline-none focus:border-emerald-500">
            <option value="77">77 Fios</option>
            <option value="120">120 Fios</option>
            <option value="150">150 Fios</option>
            <option value="165">165 Fios</option>
            <option value="Outra">Outra</option>
          </select>
        </div>

        <button type="submit" class="w-full bg-emerald-600 hover:bg-emerald-500 text-white font-semibold p-2.5 rounded transition duration-200 shadow-md">
          Adicionar à Fila
        </button>
      </form>
    </section>

    <section class="grid grid-cols-1 md:grid-cols-3 gap-6">
      
      <div class="bg-gray-800 border border-gray-700 rounded-lg p-4 shadow-md">
        <div class="flex justify-between items-center border-b border-gray-700 pb-2 mb-4">
          <h3 class="font-bold text-amber-400 flex items-center gap-2">
            <span class="w-2.5 h-2.5 rounded-full bg-amber-400"></span> A Serem Gravadas
          </h3>
          <span id="count-gravar" class="bg-gray-700 text-xs px-2 py-0.5 rounded-full text-gray-300">0</span>
        </div>
        
        <div class="relative mb-4">
          <span class="absolute inset-y-0 left-0 flex items-center pl-3 pointer-events-none text-gray-400">
            <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"></path>
            </svg>
          </span>
          <input type="text" id="input-pesquisa-gravar" class="w-full bg-gray-700 border border-gray-600 rounded pl-9 pr-3 py-2 text-sm text-white placeholder-gray-400 focus:outline-none focus:border-gray-500" placeholder="Pesquisar O.S. ou linhagem...">
        </div>

        <div id="col-gravar" class="space-y-3 min-h-[300px]"></div>
      </div>

      <div class="bg-gray-800 border border-gray-700 rounded-lg p-4 shadow-md">
        <div class="flex justify-between items-center border-b border-gray-700 pb-2 mb-4">
          <h3 class="font-bold text-blue-400 flex items-center gap-2">
            <span class="w-2.5 h-2.5 rounded-full bg-blue-400"></span> Telas Gravadas
          </h3>
          <span id="count-gravadas" class="bg-gray-700 text-xs px-2 py-0.5 rounded-full text-gray-300">0</span>
        </div>

        <div class="relative mb-4">
          <span class="absolute inset-y-0 left-0 flex items-center pl-3 pointer-events-none text-gray-400">
            <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"></path>
            </svg>
          </span>
          <input type="text" id="input-pesquisa-gravadas" class="w-full bg-gray-700 border border-gray-600 rounded pl-9 pr-3 py-2 text-sm text-white placeholder-gray-400 focus:outline-none focus:border-gray-500" placeholder="Pesquisar O.S., arte ou empresa...">
        </div>

        <div id="col-gravadas" class="space-y-3 min-h-[300px]"></div>
      </div>

      <div class="bg-gray-800 border border-gray-700 rounded-lg p-4 shadow-md opacity-75 hover:opacity-100 transition-opacity">
        <div class="flex justify-between items-center border-b border-gray-700 pb-2 mb-4">
          <h3 class="font-bold text-gray-400 flex items-center gap-2">
            <span class="w-2.5 h-2.5 rounded-full bg-gray-500"></span> Usadas / Arquivadas
          </h3>
          <span id="count-usadas" class="bg-gray-700 text-xs px-2 py-0.5 rounded-full text-gray-300">0</span>
        </div>
        
        <div class="relative mb-4">
          <span class="absolute inset-y-0 left-0 flex items-center pl-3 pointer-events-none text-gray-400">
            <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"></path>
            </svg>
          </span>
          <input type="text" id="input-pesquisa-usadas" class="w-full bg-gray-700 border border-gray-600 rounded pl-9 pr-3 py-2 text-sm text-white placeholder-gray-400 focus:outline-none focus:border-gray-500" placeholder="Pesquisar O.S., arte ou empresa...">
        </div>

        <div id="col-usadas" class="space-y-3 min-h-[300px]"></div>
      </div>

    </section>
  </main>

  <div id="modal-gravacao" class="hidden fixed inset-0 bg-black/70 flex items-center justify-center p-4 z-50 backdrop-blur-sm">
    <div class="bg-gray-800 border border-gray-700 rounded-lg p-6 w-full max-w-md shadow-2xl space-y-4">
      <h3 class="text-xl font-bold text-blue-400 border-b border-gray-700 pb-2">Detalhes da Tela Gravada</h3>
      <input type="hidden" id="modal-id-tela">
      
      <div>
        <label class="block text-sm font-medium text-gray-400 mb-1">Nome da Arte / Desenho</label>
        <input type="text" id="input-arte" class="w-full bg-gray-700 border border-gray-600 rounded p-2.5 text-white focus:outline-none focus:border-blue-500" placeholder="Ex: Logotipo Costas">
      </div>

      <div>
        <label class="block text-sm font-medium text-gray-400 mb-1">Empresa / Cliente</label>
        <input type="text" id="input-empresa" class="w-full bg-gray-700 border border-gray-600 rounded p-2.5 text-white focus:outline-none focus:border-blue-500" placeholder="Ex: Estampa Mania LTDA">
      </div>

      <div class="flex gap-3 justify-end pt-2">
        <button onclick="fecharModal()" class="px-4 py-2 bg-gray-700 hover:bg-gray-600 rounded text-sm font-medium transition">Cancelar</button>
        <button onclick="salvarDetalhesGravacao()" class="px-4 py-2 bg-blue-600 hover:bg-blue-500 text-white rounded text-sm font-medium shadow transition">Confirmar Gravada</button>
      </div>
    </div>
  </div>

  <!-- Modal do Painel Operacional (Usuários + Botão do Histórico Geral) -->
  <div id="modal-online" class="hidden fixed inset-0 bg-black/70 flex items-center justify-center p-4 z-50 backdrop-blur-sm">
    <div class="bg-gray-800 border border-gray-700 rounded-lg p-6 w-full max-w-md shadow-2xl space-y-4">
      <div class="flex justify-between items-center border-b border-gray-700 pb-2">
        <h3 class="text-xl font-bold text-emerald-400 flex items-center gap-2">
          <span class="w-2.5 h-2.5 rounded-full bg-emerald-500 animate-pulse"></span>
          Painel Operacional
        </h3>
        <button onclick="fecharModalOnline()" class="text-gray-400 hover:text-white font-bold">&times;</button>
      </div>
      
      <div>
        <h4 class="text-xs font-bold text-gray-400 uppercase tracking-wider mb-2">Usuários Conectados</h4>
        <div id="lista-usuarios-online" class="space-y-2 max-h-48 overflow-y-auto pr-1">
          <!-- Itens inseridos via JavaScript -->
        </div>
      </div>

      <div class="border-t border-gray-700 pt-3">
        <button onclick="abrirModalHistoricoAcoes()" class="w-full bg-amber-600 hover:bg-amber-500 text-white text-sm font-semibold py-2 px-4 rounded transition flex items-center justify-center gap-2">
          📋 Abrir Histórico de Ações
        </button>
      </div>

      <div class="flex justify-end pt-1">
        <button onclick="fecharModalOnline()" class="px-4 py-2 bg-gray-700 hover:bg-gray-600 rounded text-sm font-medium transition">Fechar</button>
      </div>
    </div>
  </div>

  <!-- Modal para Histórico Geral de Ações (Quem Gravou, Usou, Apagou) -->
  <div id="modal-historico-acoes" class="hidden fixed inset-0 bg-black/70 flex items-center justify-center p-4 z-50 backdrop-blur-sm">
    <div class="bg-gray-800 border border-gray-700 rounded-lg p-6 w-full max-w-2xl shadow-2xl space-y-4">
      <div class="flex justify-between items-center border-b border-gray-700 pb-2">
        <h3 class="text-xl font-bold text-amber-400 flex items-center gap-2">
          📋 Histórico Geral de Ações
        </h3>
        <button onclick="fecharModalHistoricoAcoes()" class="text-gray-400 hover:text-white font-bold">&times;</button>
      </div>
      
      <div id="lista-historico-acoes" class="space-y-2 max-h-80 overflow-y-auto pr-1 text-xs">
        <!-- Itens do Histórico inseridos via JavaScript -->
      </div>

      <div class="flex justify-end pt-2">
        <button onclick="fecharModalHistoricoAcoes()" class="px-4 py-2 bg-gray-700 hover:bg-gray-600 rounded text-sm font-medium transition">Fechar</button>
      </div>
    </div>
  </div>

  <script type="module">
    import { initializeApp } from "https://www.gstatic.com/firebasejs/10.8.0/firebase-app.js";
    import { getFirestore, collection, addDoc, onSnapshot, updateDoc, doc, deleteDoc, query, orderBy, where, getDocs, setDoc, getDoc } from "https://www.gstatic.com/firebasejs/10.8.0/firebase-firestore.js";

    const firebaseConfig = {
      apiKey: "AIzaSyC0mbq6etkxP22zko2jSu3CNxuAP6ru5ck",
      authDomain: "serigrafiasite.firebaseapp.com",
      projectId: "serigrafiasite",
      storageBucket: "serigrafiasite.firebasestorage.app",
      messagingSenderId: "422688475192",
      appId: "1:422688475192:web:f831bef2d5f862392d7ecd",
      measurementId: "G-X7H7RLF272"
    };

    const app = initializeApp(firebaseConfig);
    const db = getFirestore(app);
    const telasRef = collection(db, "telas");
    const onlineRef = collection(db, "usuarios_online");
    const historicoRef = collection(db, "historico_acoes");

    const formTela = document.getElementById("form-tela");
    const inputOs = document.getElementById("input-os");
    const selectLinhagem = document.getElementById("select-linhagem");

    const colGravar = document.getElementById("col-gravar");
    const colGravadas = document.getElementById("col-gravadas");
    const colUsadas = document.getElementById("col-usadas");
    
    const modal = document.getElementById("modal-gravacao");
    const modalIdTela = document.getElementById("modal-id-tela");
    const inputArte = document.getElementById("input-arte");
    const inputEmpresa = document.getElementById("input-empresa");
    const btnExportar = document.getElementById("btn-exportar");
    const inputImportar = document.getElementById("input-importar");

    const inputPesquisaGravar = document.getElementById("input-pesquisa-gravar");
    const inputPesquisaGravadas = document.getElementById("input-pesquisa-gravadas");
    const inputPesquisaUsadas = document.getElementById("input-pesquisa-usadas");

    let listaTelasAtual = [];
    let termoPesquisaGravar = "";
    let termoPesquisaGravadas = "";
    let termoPesquisaUsadas = "";
    let listaUsuariosOnlineAtual = [];
    let listaHistoricoAcoes = [];

    function obterDetalhesDispositivo() {
      const ua = navigator.userAgent;
      let sistema = "Desconhecido";
      let navegador = "Desconhecido";

      if (ua.includes("Win")) sistema = "Windows";
      else if (ua.includes("Android")) sistema = "Android";
      else if (ua.includes("iPhone") || ua.includes("iPad")) sistema = "iOS";
      else if (ua.includes("Mac")) sistema = "macOS";
      else if (ua.includes("Linux")) sistema = "Linux";

      if (ua.includes("Firefox")) navegador = "Firefox";
      else if (ua.includes("SamsungBrowser")) navegador = "Samsung Internet";
      else if (ua.includes("Opera") || ua.includes("OPR")) navegador = "Opera";
      else if (ua.includes("Trident")) navegador = "Internet Explorer";
      else if (ua.includes("Edge") || ua.includes("Edg")) navegador = "Microsoft Edge";
      else if (ua.includes("Chrome")) navegador = "Chrome";
      else if (ua.includes("Safari")) navegador = "Safari";

      return { sistema, navegador };
    }

    let sessionId = localStorage.getItem("serigrafia_session_id");
    if (!sessionId) {
      sessionId = "user_" + Math.random().toString(36).substr(2, 9);
      localStorage.setItem("serigrafia_session_id", sessionId);
    }

    const infoDispositivo = obterDetalhesDispositivo();
    const userDocRef = doc(db, "usuarios_online", sessionId);

    async function atualizarPresenca() {
      try {
        await setDoc(userDocRef, {
          navegador: infoDispositivo.navegador,
          sistema: infoDispositivo.sistema,
          vistoEm: Date.now()
        });
      } catch (e) {
        console.error("Erro ao atualizar presença online:", e);
      }
    }

    atualizarPresenca();
    setInterval(atualizarPresenca, 10000);

    async function registrarLog(acao, detalheOS, extras = "") {
      try {
        await addDoc(historicoRef, {
          acao: acao,
          os: detalheOS,
          extras: extras,
          usuario: `${infoDispositivo.sistema} (${infoDispositivo.navegador})`,
          data: Date.now()
        });
      } catch (e) {
        console.error("Erro ao registrar no histórico:", e);
      }
    }

    onSnapshot(onlineRef, (snapshot) => {
      const agora = Date.now();
      listaUsuariosOnlineAtual = [];

      snapshot.forEach((docSnap) => {
        const data = docSnap.data();
        if (data.vistoEm && (agora - data.vistoEm < 30000)) {
          listaUsuariosOnlineAtual.push({
            id: docSnap.id,
            navegador: data.navegador || "Outro",
            sistema: data.sistema || "Outro",
            isSelf: docSnap.id === sessionId
          });
        }
      });

      document.getElementById("count-online").innerText = listaUsuariosOnlineAtual.length;
      renderizarUsuariosOnline();
    });

    const qHist = query(historicoRef, orderBy("data", "desc"));
    onSnapshot(qHist, (snapshot) => {
      listaHistoricoAcoes = [];
      snapshot.forEach(docSnap => {
        listaHistoricoAcoes.push(docSnap.data());
      });
      renderizarHistoricoAcoes();
    });

    // Validação de Senha do Firebase ao clicar no Painel Operacional
    window.abrirModalOnline = async () => {
      const senhaDigitada = prompt("Digite a senha do Painel Operacional:");
      if (senhaDigitada === null) return;

      try {
        const docRef = doc(db, "config", "painel");
        const docSnap = await getDoc(docRef);

        if (docSnap.exists()) {
          const senhaCorreta = docSnap.data().senha;

          if (senhaDigitada.trim() === senhaCorreta.toString()) {
            document.getElementById("modal-online").classList.remove("hidden");
          } else {
            alert("Senha incorreta!");
          }
        } else {
          alert("Erro: Documento 'config/painel' com o campo 'senha' não foi localizado no Firestore.");
        }
      } catch (error) {
        console.error("Erro ao verificar senha no Firebase:", error);
        alert("Falha de conexão ao validar a senha.");
      }
    };

    window.fecharModalOnline = () => {
      document.getElementById("modal-online").classList.add("hidden");
    };

    window.abrirModalHistoricoAcoes = () => {
      fecharModalOnline();
      document.getElementById("modal-historico-acoes").classList.remove("hidden");
    };

    window.fecharModalHistoricoAcoes = () => {
      document.getElementById("modal-historico-acoes").classList.add("hidden");
    };

    function renderizarUsuariosOnline() {
      const container = document.getElementById("lista-usuarios-online");
      if (!container) return;
      container.innerHTML = "";

      if (listaUsuariosOnlineAtual.length === 0) {
        container.innerHTML = `<p class="text-xs text-gray-400">Nenhum usuário ativo no momento.</p>`;
        return;
      }

      listaUsuariosOnlineAtual.forEach((u, i) => {
        const item = document.createElement("div");
        item.className = "bg-gray-700 p-2.5 rounded border border-gray-600 flex justify-between items-center text-xs";
        item.innerHTML = `
          <div>
            <span class="font-bold text-gray-200">Sessão #${i + 1} ${u.isSelf ? '<span class="text-emerald-400 font-normal">(Você)</span>' : ''}</span>
            <div class="text-gray-400 mt-0.5">${u.sistema} • ${u.navegador}</div>
          </div>
          <span class="w-2 h-2 rounded-full bg-emerald-400"></span>
        `;
        container.appendChild(item);
      });
    }

    function renderizarHistoricoAcoes() {
      const container = document.getElementById("lista-historico-acoes");
      if (!container) return;
      container.innerHTML = "";

      if (listaHistoricoAcoes.length === 0) {
        container.innerHTML = `<p class="text-xs text-gray-400">Nenhuma ação registrada até o momento.</p>`;
        return;
      }

      listaHistoricoAcoes.forEach((item) => {
        const div = document.createElement("div");
        div.className = "bg-gray-700/60 p-2.5 rounded border border-gray-650 flex justify-between items-center";
        
        let corAcao = "text-gray-300";
        if (item.acao.includes("GRAVOU")) corAcao = "text-blue-400 font-bold";
        else if (item.acao.includes("USOU")) corAcao = "text-gray-400 font-bold";
        else if (item.acao.includes("APAGOU") || item.acao.includes("EXCLUIU")) corAcao = "text-red-400 font-bold";
        else if (item.acao.includes("CADASTROU")) corAcao = "text-emerald-400 font-bold";

        const dataStr = item.data ? new Date(item.data).toLocaleString("pt-BR") : "";

        div.innerHTML = `
          <div>
            <div class="${corAcao}">${item.acao} - O.S. #${item.os}</div>
            <div class="text-gray-400 text-[11px]">${item.extras ? item.extras + ' • ' : ''}Por: ${item.usuario}</div>
          </div>
          <div class="text-[10px] text-gray-500">${dataStr}</div>
        `;
        container.appendChild(div);
      });
    }

    formTela.addEventListener("submit", async (e) => {
      e.preventDefault();
      const numeroOS = parseInt(inputOs.value);
      const linhagemSelecionada = selectLinhagem.value+" fios";

      const osELinhagemExistemLocal = listaTelasAtual.some(t => t.os === numeroOS && t.linhagem === linhagemSelecionada);
      if (osELinhagemExistemLocal) {
        alert(`Atenção: A O.S. #${numeroOS} com linhagem de ${linhagemSelecionada} já está cadastrada no sistema.`);
        return;
      }

      try {
        const qCheck = query(telasRef, where("os", "==", numeroOS), where("linhagem", "==", linhagemSelecionada));
        const snapCheck = await getDocs(qCheck);
        
        if(!snapCheck.empty) {
          alert(`Atenção: A O.S. #${numeroOS} (${linhagemSelecionada}) já existe no banco de dados.`);
          return;
        }

        const usuarioAtual = `${infoDispositivo.sistema} (${infoDispositivo.navegador})`;

        await addDoc(telasRef, {
          os: numeroOS,
          linhagem: linhagemSelecionada,
          status: "a_gravar",
          arte: "",
          empresa: "",
          criadoPor: usuarioAtual,
          data: Date.now()
        });

        await registrarLog("CADASTROU TELA", numeroOS, `Linhagem: ${linhagemSelecionada}`);

        formTela.reset();
      } catch (error) {
        console.error("Erro ao adicionar:", error);
      }
    });

    window.abrirModalGravacao = (id, arteExistente = "", empresaExistente = "") => {
      modalIdTela.value = id;
      inputArte.value = arteExistente === "Não informada" ? "" : arteExistente;
      inputEmpresa.value = empresaExistente === "Não informada" ? "" : empresaExistente;
      modal.classList.remove("hidden");
      inputArte.focus();
    };

    window.fecharModal = () => {
      modal.classList.add("hidden");
    };

    window.salvarDetalhesGravacao = async () => {
      const id = modalIdTela.value;
      const arteVal = inputArte.value.trim() || "Não informada";
      const empresaVal = inputEmpresa.value.trim() || "Não informada";
      const usuarioAtual = `${infoDispositivo.sistema} (${infoDispositivo.navegador})`;

      if (id) {
        const docRef = doc(db, "telas", id);
        const telaAlvo = listaTelasAtual.find(t => t._idFirebase === id);
        
        await updateDoc(docRef, { 
          status: "gravada",
          arte: arteVal,
          empresa: empresaVal,
          gravadoPor: usuarioAtual
        });

        await registrarLog("GRAVOU TELA", telaAlvo ? telaAlvo.os : "?", `Arte: ${arteVal} | Cliente: ${empresaVal}`);

        fecharModal();
      }
    };

    window.moverParaUsada = async (id) => {
      const docRef = doc(db, "telas", id);
      const telaAlvo = listaTelasAtual.find(t => t._idFirebase === id);
      const usuarioAtual = `${infoDispositivo.sistema} (${infoDispositivo.navegador})`;

      await updateDoc(docRef, { 
        status: "usada",
        usadoPor: usuarioAtual
      });

      await registrarLog("USOU TELA (ARQUIVOU)", telaAlvo ? telaAlvo.os : "?");
    };

    window.restaurarTela = async (id, novoStatus) => {
      if (!novoStatus) return;
      const docRef = doc(db, "telas", id);
      const telaAlvo = listaTelasAtual.find(t => t._idFirebase === id);

      await updateDoc(docRef, { status: novoStatus });
      await registrarLog(`RESTAUROU TELA (Para ${novoStatus})`, telaAlvo ? telaAlvo.os : "?");
    };

    window.deletarTela = async (id) => {
      if(confirm("Deseja remover esta tela permanentemente do registro?")) {
        const telaAlvo = listaTelasAtual.find(t => t._idFirebase === id);
        await deleteDoc(doc(db, "telas", id));
        await registrarLog("APAGOU/EXCLUIU TELA", telaAlvo ? telaAlvo.os : "?");
      }
    };

    btnExportar.addEventListener("click", () => {
      if (listaTelasAtual.length === 0) {
        alert("Não existem dados para exportar de momento.");
        return;
      }

      let linhasTexto = [];
      linhasTexto.push("===================================================");
      linhasTexto.push("         RELATÓRIO DE CONTROLE DE TELAS - TELA USADA ");
      linhasTexto.push("===================================================\n");

      const listaInvertida = [...listaTelasAtual].reverse();

      const aGravar = listaInvertida.filter(t => t.status === "a_gravar");
      const gravadas = listaInvertida.filter(t => t.status === "gravada");
      const usadas = listaInvertida.filter(t => t.status === "usada");

      linhasTexto.push(`A SEREM GRAVADAS (${aGravar.length} telas):`);
      if(aGravar.length === 0) {
        linhasTexto.push("   Nenhuma tela pendente.");
      } else {
        aGravar.forEach(t => {
          linhasTexto.push(`   • O.S. #${t.os} | Linha: ${t.linhagem}`);
        });
      }
      linhasTexto.push("");

      linhasTexto.push(`TELAS GRAVADAS / PRONTAS (${gravadas.length} telas):`);
      if(gravadas.length === 0) {
        linhasTexto.push("   Nenhuma tela gravada pronta.");
      } else {
        gravadas.forEach(t => {
          linhasTexto.push(`   • O.S. #${t.os} | Linha: ${t.linhagem} | Arte: ${t.arte} | Empresa: ${t.empresa} | Gravado por: ${t.gravadoPor || 'Não registrado'}`);
        });
      }
      linhasTexto.push("");

      linhasTexto.push(`HISTÓRICO DE TELAS USADAS / REMOVIDAS (${usadas.length} telas):`);
      if(usadas.length === 0) {
        linhasTexto.push("   Nenhum histórico registado.");
      } else {
        usadas.forEach(t => {
          linhasTexto.push(`   • O.S. #${t.os} | Linha: ${t.linhagem} | Arte: ${t.arte} | Empresa: ${t.empresa} | Usado por: ${t.usadoPor || 'Não registrado'}`);
        });
      }

      linhasTexto.push("\nRelatório gerado em: " + new Date().toLocaleString("pt-BR"));

      const textoFinal = linhasTexto.join("\n");
      const blob = new Blob([textoFinal], { type: "text/plain;charset=utf-8" });
      const link = document.createElement("a");
      link.href = URL.createObjectURL(blob);
      link.download = `relatorio-serigrafia.txt`;
      link.click();
      URL.revokeObjectURL(link.href);
    });

    inputImportar.addEventListener("change", (e) => {
      const file = e.target.files[0];
      if (!file) return;

      const reader = new FileReader();
      reader.onload = async (event) => {
        try {
          const conteudo = event.target.result;
          const linhas = conteudo.split(/\r\n|\r|\n/);
          let statusAtual = "";
          let promessasDoLote = [];
          let tempoBase = Date.now();
          let puladosPorDuplicacao = 0;

          for (let i = 0; i < linhas.length; i++) {
            const inline_str = linhas[i].trim();
            if (!inline_str) continue;
            
            const textUpper = inline_str.toUpperCase();
            
            if (textUpper.includes("SEREM") || textUpper.includes("PENDENTE")) { 
              statusAtual = "a_gravar"; 
              continue; 
            }
            if (textUpper.includes("PRONTAS") || (textUpper.includes("GRAVADAS") && !textUpper.includes("SEREM"))) { 
              statusAtual = "gravada"; 
              continue; 
            }
            if (textUpper.includes("HISTÓRICO") || textUpper.includes("USADAS") || textUpper.includes("REMOVIDAS")) { 
              statusAtual = "usada"; 
              continue; 
            }

            if (inline_str.includes("•") || inline_str.includes("O.S.") || inline_str.includes("#")) {
              const arrPartes = inline_str.split("|");
              
              if (arrPartes.length >= 2 && statusAtual !== "") {
                const osMatch = inline_str.match(/#(\d+)/);
                if (!osMatch) continue;
                const osVal = parseInt(osMatch[1]);

                let linhagemVal = "165 Fios";
                const linhagemSeparada = arrPartes[1].split(":");
                if (linhagemSeparada.length >= 2) {
                  linhagemVal = linhagemSeparada[1].trim();
                }

                const jaExisteIdentica = listaTelasAtual.some(t => t.os === osVal && t.linhagem === linhagemVal);
                if (jaExisteIdentica) {
                  puladosPorDuplicacao++;
                  continue; 
                }

                let arteVal = "Não informada";
                let empresaVal = "Não informada";

                for (let x = 2; x < arrPartes.length; x++) {
                  const itemChave = arrPartes[x].trim();
                  if (itemChave.toLowerCase().startsWith("arte:")) {
                    arteVal = arrPartes[x].replace(/Arte:\s*/i, "").trim();
                  }
                  if (itemChave.toLowerCase().startsWith("empresa:")) {
                    empresaVal = arrPartes[x].replace(/Empresa:\s*/i, "").trim();
                  }
                }

                promessasDoLote.push(
                  addDoc(telasRef, {
                    os: osVal,
                    linhagem: linhagemVal,
                    status: statusAtual,
                    arte: arteVal,
                    empresa: empresaVal,
                    data: tempoBase - i
                  })
                );
              }
            }
          }

          if (promessasDoLote.length > 0) {
            await Promise.all(promessasDoLote);
            let msg = `Sucesso! Foram restaurados ${promessasDoLote.length} registros de telas.`;
            if (puladosPorDuplicacao > 0) {
              msg += ` (${puladosPorDuplicacao} telas repetidas com o mesmo número e tipo foram puladas).`;
            }
            alert(msg);
          } else {
            if (puladosPorDuplicacao > 0) {
              alert(`Nenhuma tela nova adicionada. Todas as ${puladosPorDuplicacao} telas desse arquivo de backup já constam no sistema.`);
            } else {
              alert("Nenhum serviço válido foi identificado dentro deste arquivo.");
            }
          }

        } catch (erroGeral) {
          console.error("Erro no processamento:", erroGeral);
          alert("Ocorreu uma falha técnica ao ler o arquivo. Veja o console.");
        }
        inputImportar.value = ""; 
      };
      reader.readAsText(file);
    });

    inputPesquisaGravar.addEventListener("input", (e) => {
      termoPesquisaGravar = e.target.value.toLowerCase().trim();
      renderizarColunas(listaTelasAtual);
    });

    inputPesquisaGravadas.addEventListener("input", (e) => {
      termoPesquisaGravadas = e.target.value.toLowerCase().trim();
      renderizarColunas(listaTelasAtual);
    });

    inputPesquisaUsadas.addEventListener("input", (e) => {
      termoPesquisaUsadas = e.target.value.toLowerCase().trim();
      renderizarColunas(listaTelasAtual);
    });

    function renderizarColunas(telas) {
      colGravar.innerHTML = ""; colGravadas.innerHTML = ""; colUsadas.innerHTML = "";
      let cGravar = 0, cGravadas = 0, cUsadas = 0;

      telas.forEach((tela) => {
        const id = tela._idFirebase; 

        const card = document.createElement("div");
        card.className = "bg-gray-700 p-3.5 rounded border border-gray-600 shadow flex flex-col justify-between space-y-3";

        if (tela.status === "a_gravar") {
          const osMatch = tela.os.toString().includes(termoPesquisaGravar);
          const linhagemMatch = tela.linhagem.toLowerCase().includes(termoPesquisaGravar);
          
          if (termoPesquisaGravar !== "" && !osMatch && !linhagemMatch) {
            return;
          }

          cGravar++;
          card.classList.add("border-l-4", "border-l-amber-500");
          card.innerHTML = `
            <div>
              <div class="text-xs text-gray-400 font-semibold uppercase tracking-wider">Ordem de Serviço</div>
              <div class="text-xl font-bold text-white">#${tela.os}</div>
              <div class="mt-1 text-sm"><span class="text-amber-400 font-medium">Tela:</span> ${tela.linhagem}</div>
              ${tela.criadoPor ? `<div class="text-[10px] text-gray-400 mt-1">Por: ${tela.criadoPor}</div>` : ''}
            </div>
            <button onclick="abrirModalGravacao('${id}')" class="w-full text-xs bg-blue-600 hover:bg-blue-500 text-white font-medium py-1.5 px-2 rounded transition">Concluir Gravação →</button>
          `;
          colGravar.appendChild(card);
        } 
        
        else if (tela.status === "gravada") {
          const osMatch = tela.os.toString().includes(termoPesquisaGravadas);
          const linhagemMatch = tela.linhagem.toLowerCase().includes(termoPesquisaGravadas);
          const arteMatch = tela.arte.toLowerCase().includes(termoPesquisaGravadas);
          const empresaMatch = tela.empresa.toLowerCase().includes(termoPesquisaGravadas);

          if (termoPesquisaGravadas !== "" && !osMatch && !linhagemMatch && !arteMatch && !empresaMatch) {
            return;
          }

          cGravadas++;
          card.classList.add("border-l-4", "border-l-blue-500");
          card.innerHTML = `
            <div class="space-y-2">
              <div class="flex justify-between items-start">
                <div>
                  <div class="text-xs text-gray-400 font-semibold uppercase tracking-wider">Ordem de Serviço</div>
                  <div class="text-xl font-bold text-white">#${tela.os}</div>
                </div>
                <span class="text-xs bg-gray-800 px-2 py-0.5 rounded text-blue-300 font-medium">${tela.linhagem}</span>
              </div>
              <div onclick="abrirModalGravacao('${id}', '${tela.arte}', '${tela.empresa}')" class="bg-gray-800/50 p-2 rounded text-xs space-y-1 border border-gray-650 cursor-pointer hover:bg-gray-800/80 transition duration-150" title="Clique para editar as informações">
                <p class="text-gray-300"><span class="text-gray-500 font-medium">Arte:</span> ${tela.arte}</p>
                <p class="text-gray-300"><span class="text-gray-500 font-medium">Empresa:</span> ${tela.empresa}</p>
                ${tela.gravadoPor ? `<p class="text-[10px] text-blue-300 pt-1 border-t border-gray-700/50">Gravado por: ${tela.gravadoPor}</p>` : ''}
              </div>
            </div>
            <button onclick="moverParaUsada('${id}')" class="w-full text-xs bg-gray-600 hover:bg-gray-500 text-white font-medium py-1.5 px-2 rounded transition">Remover (Tela Usada) ✓</button>
          `;
          colGravadas.appendChild(card);
        } 
        
        else if (tela.status === "usada") {
          const osMatch = tela.os.toString().includes(termoPesquisaUsadas);
          const arteMatch = tela.arte.toLowerCase().includes(termoPesquisaUsadas);
          const empresaMatch = tela.empresa.toLowerCase().includes(termoPesquisaUsadas);
          
          if (termoPesquisaUsadas !== "" && !osMatch && !arteMatch && !empresaMatch) {
            return;
          }

          cUsadas++;
          card.classList.add("border-l-4", "border-l-gray-500", "bg-opacity-50");
          card.innerHTML = `
            <div class="flex justify-between items-start">
              <div>
                <div class="text-xs text-gray-500 font-semibold uppercase tracking-wider line-through"><strong>Op: </strong>#${tela.os}</div>
                <div class="text-sm text-gray-400 font-medium"><strong>Lineatura: </strong>${tela.linhagem} <br><strong>Arte:</strong> ${tela.arte} <br><strong>Empresa: </strong>${tela.empresa}</div>
                ${tela.usadoPor ? `<div class="text-[10px] text-gray-400 mt-1">Usado por: ${tela.usadoPor}</div>` : ''}
              </div>
              <div class="flex flex-col items-end gap-1">
                <select onchange="restaurarTela('${id}', this.value)" class="bg-gray-800 border border-gray-600 rounded text-xs text-emerald-400 font-medium p-1 focus:outline-none cursor-pointer">
                  <option value="" disabled selected>Restaurar ▾</option>
                  <option value="a_gravar">→ A Ser Gravada</option>
                  <option value="gravada">→ Tela Gravada</option>
                </select>
                <button onclick="deletarTela('${id}')" class="text-red-400 hover:text-red-500 text-xs font-bold p-1">Excluir</button>
              </div>
            </div>
          `;
          colUsadas.appendChild(card);
        }
      });

      document.getElementById("count-gravar").innerText = cGravar;
      document.getElementById("count-gravadas").innerText = cGravadas;
      document.getElementById("count-usadas").innerText = cUsadas;
    }

    const q = query(telasRef, orderBy("data", "desc"));
    onSnapshot(q, (snapshot) => {
      listaTelasAtual = []; 

      snapshot.forEach((doc) => {
        const tela = doc.data();
        tela._idFirebase = doc.id; 
        listaTelasAtual.push(tela);
      });

      renderizarColunas(listaTelasAtual);
    });
  </script>
</body>
</html>
