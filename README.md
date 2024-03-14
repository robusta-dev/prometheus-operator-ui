# PrometheusRule Editor

A web UI to create PrometheusRules on Kubernetes. Supports kube-prometheus-stack and the Prometheus operator.

## Sample

![PrometheusRule Generator in action](./image/PrometheusRuleGeneratordemo.png)

## Features
- [x] Auto-generate PrometheusRule YAML
- [x] Supports clusters with multiple Prometheus
- [x] Add selector labels to YAML by default
- [x] Auto-detect multiple Prometheuses
- [x] Switch between multiple Prometheuses in the UI
- [x] Check namespaces for `ruleNamespaceSelectors`

## Try it out

1. Clone the repository 
```bash
git clone https://github.com/robusta-dev/prometheus-operator-ui.git && cd prometheus-operator-ui
```

2. Install dependencies

```bash
pip install -r requirements.txt    
```

3. Run the web app
```bash
streamlit run main.py
```

4. Go to [http://localhost:8501](http://localhost:8501)

