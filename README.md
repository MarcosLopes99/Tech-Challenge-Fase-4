# Tech Challenge Fase 4 - Grupo 14
- Marcelo Henriques da Fonseca - RM353865
- Marcos Lopes da Silva Junior - RM353763
- Ricardo Báfica Pontes - RM353866

Link para o vídeo mostrando o projeto: 
Link para o vídeo output:

O problema:

O Tech Challenge desta fase será a criação de uma aplicação que utilize análise de vídeo. O seu projeto deve incorporar as técnicas de reconhecimento facial, análise de expressões emocionais em vídeos e detecção de atividades.

A proposta do desafio:

Você deverá criar uma aplicação a partir do vídeo que se encontra disponível na plataforma do aluno, e que execute as seguintes tarefas:
- Reconhecimento facial: Identifique e marque os rostos presentes no vídeo.
- Análise de expressões emocionais: Analise as expressões emocionais dos rostos identificados.
- Detecção de atividades: Detecte e categorize as atividades sendo realizadas no vídeo.
- Geração de resumo: Crie um resumo automático das principais atividades e emoções detectadas no vídeo.

O que esperamos como entregáveis:

- Código Fonte: todo o código fonte da aplicação deve ser entregue em um repositório Git, incluindo um arquivo README com instruções claras de como executar o projeto.
- Relatório: o resumo obtido automaticamente com as principais atividades e emoções detectadas no vídeo. Nesse momento esperando que o relatório inclua: . Total de frames analisados. . Número de anomalias detectadas.
- Observação: movimento anômalo não segue o padrão geral de atividades (como gestos bruscos ou comportamentos atípicos) esses são classificados como anômalos.
- Demonstração em Vídeo: um vídeo demonstrando a aplicação em funcionamento, evidenciando cada uma das funcionalidades implementadas.

Projeto proposto pelos alunos:

As emoções:

Detectaremos as seguintes emoções/expressões faciais presentes no vídeo:
- "Triste"
- "Bravo"
- "Surpreso"
- "Medo"
- "Feliz"
- "Nojo"
- "Neutro"
- "Careta"
Das emoções citadas, "Careta" configurará uma anomalia a ser detectada.

As atividades:

Detectaremos as seguintes atividades presentes no vídeo:
- "Mão levantada"
- "Mão no rosto"

Os entregáveis:

Código em python que trata o vídeo oferecido pela FIAP e gera os seguintes entregáveis:
- Vídeo "output" baseado no vídeo original, mostrando rostos detectados, emoções detectadas e atividades detectadas
- Arquivo com histórico completo das emoções/atividades detectadas no vídeo, registrando todas as emoções/atividades detectadas no vídeo
- Arquivo com histórico parcial das emoções/atividades detectadas no vídeo, registrando apenas as emoções/atividades detectadas no frame mediano de cada segundo
- Relatório resumindo as detecções realizadas no vídeo, incluindo o número total de frames analisados e o total de anomalias (caretas) detectadas
Este projeto propõe a captura de um único frame específico entre os 30 registrados a cada segundo de vídeo para a criação de um histórico parcial que seria de leitura mais fácil para um ser humano. A percepção humana de movimento contínuo ocorre a partir de 24 frames por segundo, tendo sido este o padrão básico estabelecido pela indústria cinematográfica para seus filmes. No entanto, as emoções faciais humanas tendem a permanecer estáveis por períodos superiores a 1 segundo. Por isso, acreditamos que essa abordagem pode ser eficaz para identificar mudanças significativas nas emoções, sem comprometer a precisão das informações analisadas.
