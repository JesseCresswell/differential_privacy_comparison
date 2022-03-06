# differential_privacy_comparison
Comparing GDP and RDP for accounting the privacy budget of DP-SGD

# RDP 1 epochs: epsilon=0.68 at delta=1e-5
python main.py --device=cpu --epochs=1 --accountant=rdp

# GDP 1 epochs: epsilon=0.14 at delta=1e-5
python main.py --device=cpu --epochs=1 --accountant=gdp

# RDP 10 epochs: epsilon=0.80 at delta=1e-5
python main.py --device=cpu --epochs=10 --accountant=rdp

# GDP 10 epochs: epsilon=0.47 at delta=1e-5
python main.py --device=cpu --epochs=10 --accountant=gdp