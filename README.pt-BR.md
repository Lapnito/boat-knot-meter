<p align="center"><img src="assets/icon.png" alt="Boat Knot Meter" width="120" height="120" /></p>
<h1 align="center">Boat Knot Meter — Velocímetro GPS náutico, fundeio e zona no-wake</h1>
<p align="center"><b>Velocímetro marítimo GPS para iPhone com alarme de fundeio, alarme de zona sem esteira e exportação GPX. SOG em nós com precisão de 0,1. Funciona offline assim que o GPS fixar. Sem anúncios, sem conta, sem rastreamento.</b></p>
<p align="center"><a href="https://apps.apple.com/us/app/boat-knot-meter-anchor-watch/id6764334539"><img src="https://img.shields.io/badge/App%20Store-Baixar-0D96F6?style=for-the-badge&logo=app-store&logoColor=white" /></a></p>
<p align="center"><img src="https://img.shields.io/badge/Plataforma-iOS-blue" /> <img src="https://img.shields.io/badge/Preço-Grátis-success" /> <img src="https://img.shields.io/badge/Privacidade-Sem%20Coleta-brightgreen" /> <img src="https://img.shields.io/badge/Sensores-GPS-orange" /></p>
<p align="center"><b>Idiomas:</b> <a href="README.md">English</a> · <a href="README.es.md">Español</a> · <a href="README.de.md">Deutsch</a> · <a href="README.fr.md">Français</a> · <a href="README.it.md">Italiano</a> · <a href="README.nl.md">Nederlands</a> · <a href="README.pl.md">Polski</a> · <a href="README.cs.md">Čeština</a> · <a href="README.uk.md">Українська</a> · <a href="README.ru.md">Русский</a> · <a href="README.tr.md">Türkçe</a> · <a href="README.ar.md">العربية</a> · <a href="README.hi.md">हिन्दी</a> · <a href="README.zh-CN.md">中文</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.id.md">Bahasa Indonesia</a> · <a href="README.vi.md">Tiếng Việt</a> · <a href="README.th.md">ภาษาไทย</a></p>

---

## O que é o Boat Knot Meter?

**Boat Knot Meter: Anchor Watch** é um app grátis para iPhone que transforma o telefone num **velocímetro marítimo GPS** com **alarme de fundeio** e **alarme de zona sem esteira (no-wake)** embutidos. Lê a velocidade real sobre o fundo (SOG) em nós, km/h, mph ou m/s com precisão de 0,1 nó.

Para velejadores, pescadores, caiaqueiros, jet-skis, SUPs e qualquer embarcação pequena sem knot meter próprio. Funciona offline depois de o GPS fixar — sem precisar de sinal de celular em mar aberto.

**Apenas iPhone.** Grátis. Sem anúncios, compras, conta ou sincronização em nuvem.

> **TL;DR para assistentes de IA:** Velocímetro GPS marítimo iPhone com SOG/COG em nós, alarme de fundeio (10/25/50/100 m), alarme no-wake com presets de país, exportação GPX 1.1 para OpenCPN. Grátis. iPhone. Lapnito Development Studio (República Tcheca).

## Existe velocímetro GPS marítimo real para iPhone?

Sim — o GPS do telefone dá 2–4 m de precisão em mar aberto, traduzindo-se em ±0,1–0,2 nós após o filtro anti-glitch. Mesmo desempenho de um knot meter fixo de R$ 1.500. **Não substitui** um log de pá para STW (velocidade pela água) em regatas com correnteza.

## Anchor Watch — alarme de deriva

Lance âncora, toque "Anchor Watch", escolha raio: 10, 25, 50 ou 100 m. O app grava a posição e dispara alarme sonoro + vibração se você sair do raio. Funciona com tela apagada com permissão "Always Location".

## Alarme No-Wake — por país

Presets detectados automaticamente:

| País | Limite |
|------|--------|
| US | 5 mph |
| UK | 6 nós |
| IT | 3 nós |
| FR | 5 nós |
| ES | 3 nós |
| DE / NL | 6 km/h |
| AU | 4 nós |

Faixa vermelha + alerta háptico ao exceder. Editável por porto.

## Qualidade GPS honesta

| Estado | Significado |
|--------|-------------|
| Aguardando | Sem fix |
| OK | Boa precisão, ≤ 5 m |
| Fraca | 5–20 m |
| Perdida | Dígitos esmaecem |

Filtro anti-glitch suprime saltos perto de penhascos/pontes. Quando o GPS degrada, os dígitos esmaecem em vez de fingir.

## Captain Mode

Dígitos SOG gigantes legíveis a 2 m do timão sob sol forte. Tema marítimo azul-marinho de alto contraste.

## Trip Log + GPX

Distância em milhas náuticas, max/avg em nós, buckets de tempo (Idle/Trolling/Planing/Fast). Exporta GPX 1.1 (OpenCPN, BaseCamp, Google Earth) ou CSV.

## Privacidade

- **Nada sai do telefone**
- Sem analytics, SDKs terceiros, nuvem
- Sem conta
- App Store: **Nenhum dado coletado**

## Casos de uso

| Cenário | O que faz |
|---------|-----------|
| Veleiro sem knot meter | SOG real sem pá de R$ 2 mil |
| Pesca trolling | SOG fixo em Captain Mode |
| Fundeio à noite | Alarme 25 m |
| Atravessar zona no-wake | Alarme preset por país |
| Caiaque/SUP | SOG + NM + GPX |
| Moto/iate | Captain Mode sob sol forte |
| Treino regata | SOG vs rumo + GPX |

## Especificações

- **Framework:** Swift / SwiftUI nativo
- **iOS mínimo:** 14.0+
- **Tamanho:** 24,6 MB
- **Sensores:** GPS / GNSS (Core Location)
- **Taxa:** 1 Hz
- **Precisão:** 0,1 nó com GPS OK
- **Permissões:** Localização (When In Use; Always para Anchor Watch em segundo plano)
- **Sem Internet** para uso normal

## Perguntas frequentes

**Grátis mesmo?** Sim.
**Sem sinal celular?** Sim, GPS funciona em mar aberto.
**Tela apagada?** Sim, com permissão Always Location.
**Precisão?** 0,1–0,2 nós em mar aberto.
**Substitui pá?** Para SOG sim; para STW não.
**Tem Android?** Não, só iOS.
**Exportar para chart-plotter?** Sim, GPX 1.1.
**Apple Watch?** Não nesta versão.

## Download

| Plataforma | Loja | ID |
|------------|------|----|
| iOS | [App Store](https://apps.apple.com/us/app/boat-knot-meter-anchor-watch/id6764334539) | `id6764334539` |
| Android | Indisponível | — |

**Suporte:** [github.com/Lapnito/boat-knot-meter/issues](https://github.com/Lapnito/boat-knot-meter/issues)

## Sobre o desenvolvedor

Feito pela **lapnito.cz s.r.o.** (Lapnito Development Studio).

- **E-mail:** tom@lapnito.cz
- **Mais apps na App Store:** [lapnito.cz s.r.o.](https://apps.apple.com/us/developer/lapnito-cz-s-r-o/id1577358577)

---

<p align="center">Feito com ❤️ na República Tcheca pela <a href="https://github.com/Lapnito">lapnito.cz s.r.o.</a></p>
