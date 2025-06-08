FROM nicolargo/glances:latest
COPY glances.conf /root/.config/glances/glances.conf
CMD ["python", "-m", "glances", "-C", "/root/.config/glances/glances.conf"]
