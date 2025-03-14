# Pesquisa da aula do dia 12/02

## O que é arquitetura AMD 64?

- É uma arquitetura de processador de 64 bits desenvolvida inicialmente pela **AMD** (Advanced Micro Devices).

### Pontos chave:

1. Largura de dados, ou seja, a capacidade de processar dados em "blocos" maiores. Um processador de 64 bits pode manipular muito mais dados por vez, acessar uma memória significativamente maior (até 16 exabytes, embora a limitação prática seja muito menor), e melhorar o desempenho em tarefas que exigem grande capacidade computacional.
2. Compatibilidade, a arquitetura AMD64 foi projetada para ser compatível com software de 32 bits. Isso significa que sistemas e programas de 32 bits podem ser executados em um processador AMD64, mas os benefícios de desempenho só são alcançados quando o sistema e o software são de 64 bits.
3. Evolução: A AMD64 foi a primeira arquitetura de 64 bits amplamente adotada para PCs. Ela foi lançada em 2003 e posteriormente adotada pela **Intel** em seus próprios processadores, sob a marca **Intel 64**. Embora a AMD tenha sido pioneira, hoje em dia, processadores de 64 bits, seja da AMD ou Intel, são comuns em desktops, laptops e servidores.

### Vantagens:

1. **Maior capacidade de memória**: Em um sistema de 32 bits, o limite de memória é de 4 GB. Em um sistema de 64 bits, esse limite é praticamente ilimitado (na prática, a memória disponível é limitada pelas especificações da placa-mãe e do sistema operacional).
2. **Desempenho superior**: Processadores de 64 bits podem processar dados mais rapidamente, especialmente em tarefas pesadas como edição de vídeos, modelagem 3D, e execução de máquinas virtuais.
- Quando você ouvir sobre "AMD64", está se referindo a um conjunto de instruções e uma arquitetura de processador de 64 bits originalmente desenvolvida pela AMD, mas que agora é amplamente utilizada em sistemas modernos, tanto da AMD quanto da Intel.

## Quais as arquiteturas utilizadas nos dispositivos móveis hoje?

### ARM (Advanced RISC Machine)

- A ARM não fabrica seus próprios processadores, mas desenvolve a arquitetura e licencia seus designs para outras empresas que fabricam os chips. Isso torna os processadores ARM mais acessíveis e flexíveis em termos de personalização. As variantes mais comuns da arquitetura ARM incluem:
1. **ARMv7** (32 bits): Era muito comum em dispositivos móveis mais antigos, mas está sendo substituído por versões de 64 bits.
2. **ARMv8-A** (64 bits): Essa versão trouxe a transição para processadores de 64 bits, o que permite uma maior capacidade de processamento e maior acesso à memória. Todos os processadores modernos da linha **Snapdragon, Exynos, Apple A-series**, e **Kirin** (da Huawei) utilizam variantes dessa arquitetura.

A **ARM** se destaca pelo seu baixo consumo de energia, o que é essencial para manter a vida útil da bateria em dispositivos móveis, além de ser altamente eficiente no processamento de tarefas específicas.

**Exemplos de chipsets ARM populares:**

- **Qualcomm Snapdragon** (ex: Snapdragon 8 Gen 2)
- **Apple A-Series** (ex: A14, A15, M1, M2)
- **Samsung Exynos**
- **HiSilicon Kirin** (da Huawei)

Esses chipsets são usados em uma ampla variedade de dispositivos móveis, como iPhones, smartphones Android e tablets.

### x86 (Intel/AMD)

- A arquitetura **x86**, que é mais conhecida em PCs e laptops, também é usada em alguns dispositivos móveis, embora de forma menos comum. Processadores **x86-64** (64 bits) são produzidos pela **Intel** e **AMD**, mas, por questões de consumo de energia e otimização para dispositivos móveis, os chips **ARM** dominaram o mercado de smartphones e tablets.

A Intel, por exemplo, lançou chips móveis com a arquitetura x86, como os da linha **Intel Atom**, que foram usados em alguns dispositivos Android e até em alguns **tablets Windows**. No entanto, os chips **x86** são muito mais populares em laptops e desktops.

## O que falta no modelo de Von Neumann?

1. **Gargalo de Von Neumann**: O acesso sequencial à memória para dados e instruções pode diminuir o desempenho devido à largura de banda limitada entre a CPU e a memória.
2. **Memória Única para Dados e Instruções**: Armazenar dados e instruções na mesma memória pode ser ineficiente e inseguro (ex.: vulnerabilidades de segurança).
3. **Processamento Sequencial**: O modelo de Von Neumann não foi feito para paralelismo, limitando o desempenho em tarefas que exigem processamento paralelo.
4. **Eficiência Energética**: O modelo não foi otimizado para baixo consumo de energia, o que pode ser problemático em dispositivos móveis e sistemas modernos.
5. **Falta de Instruções Específicas**: Ele não é eficiente para operações especializadas (como gráficos ou IA), que exigem arquiteturas específicas como GPUs ou TPUs.
- Essas limitações levaram ao desenvolvimento de arquiteturas alternativas e melhorias no design dos sistemas computacionais.