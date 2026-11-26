# Анализ устойчивости причинно-следственных графов, восстановленных по многомерным временным рядам

[![License](https://badgen.net/github/license/intsystems/2027-Project-212?color=green)](https://github.com/intsystems/2027-Project-212/blob/main/LICENSE)
[![GitHub Contributors](https://img.shields.io/github/contributors/intsystems/2027-Project-212)](https://github.com/intsystems/2027-Project-212/graphs/contributors)
[![GitHub Issues](https://img.shields.io/github/issues-closed/intsystems/2027-Project-212.svg?color=0088ff)](https://github.com/intsystems/2027-Project-212/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr-closed/intsystems/2027-Project-212.svg?color=7f29d6)](https://github.com/intsystems/2027-Project-212/pulls)

<table>
    <tr>
        <td align="left"> <b> Author </b> </td>
        <td> Григорий Новичков </td>
    </tr>
    <tr>
        <td align="left"> <b> Consultant </b> </td>
        <td> Не указан </td>
    </tr>
    <tr>
        <td align="left"> <b> Advisor </b> </td>
        <td> Вадим Викторович Стрижов </td>
    </tr>
</table>

## Assets

- [LinkReview](LINKREVIEW.md)
- [Code](code)
- [Paper](paper/main.pdf)
- [Slides](slides/main.pdf)

## Abstract

Исследуем, влечёт ли неизменность состояния динамической системы неизменность
причинно-следственного графа, восстановленного по многомерным временным рядам.

Гипотеза: в пределах одного процесса структура графа остаётся устойчивой,
а при смене процесса меняется. Проверяем, насколько чувствительны изменения
графа к переходам между процессами.

В первом эксперименте на данных HARTH рассматриваем ходьбу и бег как два режима
движения. Восстанавливаем графы по фрагментам сигналов акселерометров и проверяем,
можно ли различать эти режимы по признакам графов.

## Citation

If you find our work helpful, please cite us.
```BibTeX
@misc{novichkov2026causalgraphs,
    title={Анализ устойчивости причинно-следственных графов, восстановленных по многомерным временным рядам},
    author={Новичков, Григорий},
    year={2026},
    url={https://github.com/intsystems/2027-Project-212}
}
```

## Licence

Our project is MIT licensed. See [LICENSE](LICENSE) for details.
