<ol>
<li>LigandScout与REINVENT联用，实现深度增强学习从头设计DDR1抑制剂</li>
<p>Yoshimori, A.; Asawa, Y.; Kawasaki, E.; Tasaka, T.; Matsuda, S.; Sekikawa, T.; Tanabe, S.; Neya, M.; Natsugari, H.; Kanai, C. Design and Synthesis of DDR1 Inhibitors with a Desired Pharmacophore Using Deep Generative Models. ChemMedChem 2021, 16 (6), 955–958. https://doi.org/10.1002/cmdc.202000786.</p>

<li>LigandScout与REINVENT联用，实现深度增强学习从头设计TIE2选择性抑制剂</li>
<p>Yoshimori, A.; Kawasaki, E.; Kanai, C.; Tasaka, T. Strategies for Design of Molecular Structures with a Desired Pharmacophore Using Deep Reinforcement Learning. Chem. Pharm. Bull. 2020, 68 (3), 227–233. DOI：10.1248/cpb.c19-00625.</p>

<p>LigandScout是一款主打药效团的药物设计平台，支持基于结构与基于配体的药效团识别与虚拟筛选。如果您有蛋白结构、或复合物结构、或至少一个配体结构，理论上都可以生成药效团假设，然后与REINVENT联用进行从头药物分子设计。</p>

<li>形状技术（OpenEye/ROCS）以及分子对接技术（OpenEye/FRED）与REINVET联用,实现增强学习从头设计</p>
Thomas, M.; Smith, R. T.; O’Boyle, N. M.; de Graaf, C.; Bender, A. Comparison of Structure- and Ligand-Based Scoring Functions for Deep Generative Models: A GPCR Case Study. J. Cheminform. 2021, 13 (1), 39. https://doi.org/10.1186/s13321-021-00516-0.

<p>ROCS是基于形状的技术，理论上你只有一个已知的活性化合物就可以建立形状query进行增强学习训练。而FRED分子对接技术则仅要求有一个蛋白，可以没有任何已知的活性化合物，就可以增强学习训练实现从头分子设计。</p>

<p>相关的代码实现见：https://github.com/MorganCThomas/MolScore</p>

<li>关于深度学习结构设计开源软件REINVENT</li>
<p>Ligandscout、ROCS与FRED等代表的药效团、形状与分子对接技术在增强学习中作为打分函数，而REINVENT则是深度增强学习从头设计的基础框架，由AZ开发、开源且免费。</p>
<p>Olivecrona, M.; Blaschke, T.; Engkvist, O.; Chen, H. Molecular De-Novo Design through Deep Reinforcement Learning. J. Cheminform. 2017, 9 (1), 48. https://doi.org/10.1186/s13321-017-0235-x.</p>
<p>Blaschke, T.; Arús-Pous, J.; Chen, H.; Margreitter, C.; Tyrchan, C.; Engkvist, O.; Papadopoulos, K.; Patronov, A. REINVENT 2.0: An AI Tool for De Novo Drug Design. J. Chem. Inf. Model. 2020, 60 (12), 5918–5922. https://doi.org/10.1021/acs.jcim.0c00915.</p>

<p>REINVENT: https://github.com/MolecularAI/Reinvent</p>
<p>REINVENT 2.0: https://github.com/MolecularAI/Reinvent</p>

<li>Deep Docking: OpenEye/FRED与深度学习联用实现超大规模虚拟筛选</li>
<p>对代表性化合物先用FRED进行docking计算，获得打分值；接着用深度学习进行训练，获得可以区分打分高、低的深度学习模型；用该深度学习模型对超大规模数据库进行虚拟筛，然后再用docking进行对上一步的化合物进行对接虚拟筛选。</p>
<p>Gentile, F.; Agrawal, V.; Hsing, M.; Ton, A.-T.; Ban, F.; Norinder, U.; Gleave, M. E.; Cherkasov, A. Deep Docking: A Deep Learning Platform for Augmentation of Structure Based Drug Discovery. ACS Cent. Sci. 2020, 6 (6), 939–949. https://doi.org/10.1021/acscentsci.0c00229.</p>
