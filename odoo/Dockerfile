# Base official Odoo image
FROM odoo:16.0

# Set database host to the linked container alias
ENV DB_HOST=db
# Optional: you can also set other defaults
# ENV DB_PORT=5432
# ENV DB_USER=odoo
# ENV DB_PASSWORD=odoo

# Expose Odoo port
EXPOSE 8069

# Default to Odoo user
USER odoo

# Start Odoo (uses environment variables for DB connection)
CMD ["odoo"]
