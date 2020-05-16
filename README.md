# OffenseEval2020
OffenseEval2020 Competetion

# Results
<table>
<thead>
  <tr>
    <th>Technique</th>
    <th>Arabic</th>
    <th>Turkish</th>
    <th>Danish</th>
    <th>Greek</th>
    <th>English*</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Count Vectorizer features</td>
    <td>0.80</td>
    <td>0.71</td>
    <td>0.75</td>
    <td>0.76</td>
    <td>0.67</td>
  </tr>
  <tr>
    <td>TF-IDF Word level features</td>
    <td>0.79</td>
    <td>0.69</td>
    <td>0.71</td>
    <td>0.75</td>
    <td>0.68</td>
  </tr>
  <tr>
    <td>TF-IDF Char level features</td>
    <td>0.85</td>
    <td>0.73</td>
    <td>0.76</td>
    <td>0.80</td>
    <td>0.69</td>
  </tr>
  <tr>
    <td>Bi LSTM followed by Bi GRU</td>
    <td>0.84</td>
    <td>0.72</td>
    <td>0.72</td>
    <td>0.78</td>
    <td>0.72</td>
  </tr>
  <tr>
    <td>Bi LSTM followed by Bi GRU with attention</td>
    <td>0.84</td>
    <td>0.71</td>
    <td>0.73</td>
    <td>0.77</td>
    <td>0.72</td>
  </tr>
  <tr>
    <td>Temporal Convolution Network</td>
    <td>0.84</td>
    <td>0.72</td>
    <td>0.62</td>
    <td>0.79</td>
    <td>0.71</td>
  </tr>
  <tr>
    <td>Convolution Neural Network</td>
    <td>0.80</td>
    <td>0.71</td>
    <td>0.58</td>
    <td>0.74</td>
    <td>0.72</td>
  </tr>
</tbody>
</table>


* in english [OLID dataset](https://github.com/talhaanwarch/Offensive-Language-Detection) is used



# Position in competetion
![Image description](result.png)

