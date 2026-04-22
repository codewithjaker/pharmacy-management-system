```json
├── app/
│   ├── (auth)/
│   │   ├── login/
│   │   │   ├── page.tsx
│   │   │   └── loading.tsx
│   │   ├── register/
│   │   │   ├── page.tsx
│   │   │   └── loading.tsx
│   │   ├── forgot-password/
│   │   │   └── page.tsx
│   │   ├── reset-password/
│   │   │   └── page.tsx
│   │   └── layout.tsx
│   ├── (admin)/
│   │   ├── layout.tsx
│   │   ├── dashboard/
│   │   │   ├── page.tsx
│   │   │   ├── loading.tsx
│   │   │   └── error.tsx
│   │   ├── users/
│   │   │   ├── page.tsx
│   │   │   ├── loading.tsx
│   │   │   ├── [id]/
│   │   │   │   ├── page.tsx
│   │   │   │   ├── edit/
│   │   │   │   │   └── page.tsx
│   │   │   │   └── loading.tsx
│   │   │   ├── add/
│   │   │   │   └── page.tsx
│   │   │   └── roles/
│   │   │       └── page.tsx
│   │   ├── pharmacies/
│   │   │   ├── page.tsx
│   │   │   ├── [id]/
│   │   │   │   ├── page.tsx
│   │   │   │   └── edit/
│   │   │   │       └── page.tsx
│   │   │   └── add/
│   │   │       └── page.tsx
│   │   ├── system/
│   │   │   ├── settings/
│   │   │   │   └── page.tsx
│   │   │   ├── audit-logs/
│   │   │   │   └── page.tsx
│   │   │   ├── backup/
│   │   │   │   └── page.tsx
│   │   │   └── notifications/
│   │   │       └── page.tsx
│   │   └── analytics/
│   │       ├── page.tsx
│   │       ├── system-usage/
│   │       │   └── page.tsx
│   │       └── financial/
│   │           └── page.tsx
│   ├── (dashboard)/
│   │   ├── layout.tsx
│   │   ├── page.tsx
│   │   ├── loading.tsx
│   │   ├── error.tsx
│   │   ├── inventory/
│   │   │   ├── page.tsx
│   │   │   ├── loading.tsx
│   │   │   ├── [id]/
│   │   │   │   ├── page.tsx
│   │   │   │   └── loading.tsx
│   │   │   ├── add/
│   │   │   │   └── page.tsx
│   │   │   ├── categories/
│   │   │   │   └── page.tsx
│   │   │   └── batches/
│   │   │       └── page.tsx
│   │   ├── patients/
│   │   │   ├── page.tsx
│   │   │   ├── [id]/
│   │   │   │   ├── page.tsx
│   │   │   │   ├── medical-history/
│   │   │   │   │   └── page.tsx
│   │   │   │   └── prescriptions/
│   │   │   │       └── page.tsx
│   │   │   └── add/
│   │   │       └── page.tsx
│   │   ├── sales/
│   │   │   ├── page.tsx
│   │   │   ├── [id]/
│   │   │   │   ├── page.tsx
│   │   │   │   └── invoice/
│   │   │   │       └── page.tsx
│   │   │   ├── pos/
│   │   │   │   └── page.tsx
│   │   │   └── returns/
│   │   │       └── page.tsx
│   │   ├── prescriptions/
│   │   │   ├── page.tsx
│   │   │   ├── [id]/
│   │   │   │   └── page.tsx
│   │   │   ├── new/
│   │   │   │   └── page.tsx
│   │   │   └── pending/
│   │   │       └── page.tsx
│   │   ├── suppliers/
│   │   │   ├── page.tsx
│   │   │   ├── [id]/
│   │   │   │   └── page.tsx
│   │   │   ├── add/
│   │   │   │   └── page.tsx
│   │   │   └── orders/
│   │   │       ├── page.tsx
│   │   │       ├── [id]/
│   │   │       │   └── page.tsx
│   │   │       └── new/
│   │   │           └── page.tsx
│   │   ├── reports/
│   │   │   ├── page.tsx
│   │   │   ├── sales/
│   │   │   │   └── page.tsx
│   │   │   ├── inventory/
│   │   │   │   └── page.tsx
│   │   │   ├── financial/
│   │   │   │   └── page.tsx
│   │   │   └── custom/
│   │   │       └── page.tsx
│   │   └── settings/
│   │       ├── page.tsx
│   │       ├── profile/
│   │       │   └── page.tsx
│   │       ├── pharmacy/
│   │       │   └── page.tsx
│   │       └── security/
│   │           └── page.tsx
│   ├── api/
│   │   ├── auth/
│   │   │   ├── [...nextauth]/
│   │   │   │   └── route.ts
│   │   │   ├── login/
│   │   │   │   └── route.ts
│   │   │   ├── register/
│   │   │   │   └── route.ts
│   │   │   └── logout/
│   │   │       └── route.ts
│   │   ├── v1/
│   │   │   ├── admin/
│   │   │   │   ├── users/
│   │   │   │   │   ├── route.ts
│   │   │   │   │   └── [id]/
│   │   │   │   │       └── route.ts
│   │   │   │   ├── pharmacies/
│   │   │   │   │   ├── route.ts
│   │   │   │   │   └── [id]/
│   │   │   │   │       └── route.ts
│   │   │   │   ├── system/
│   │   │   │   │   ├── audit-logs/
│   │   │   │   │   │   └── route.ts
│   │   │   │   │   ├── backup/
│   │   │   │   │   │   └── route.ts
│   │   │   │   │   └── settings/
│   │   │   │   │       └── route.ts
│   │   │   │   └── analytics/
│   │   │   │       └── route.ts
│   │   │   ├── inventory/
│   │   │   │   ├── route.ts
│   │   │   │   ├── [id]/
│   │   │   │   │   └── route.ts
│   │   │   │   ├── categories/
│   │   │   │   │   └── route.ts
│   │   │   │   └── batches/
│   │   │   │       └── route.ts
│   │   │   ├── patients/
│   │   │   │   ├── route.ts
│   │   │   │   └── [id]/
│   │   │   │       └── route.ts
│   │   │   ├── sales/
│   │   │   │   ├── route.ts
│   │   │   │   └── [id]/
│   │   │   │       └── route.ts
│   │   │   ├── prescriptions/
│   │   │   │   ├── route.ts
│   │   │   │   └── [id]/
│   │   │   │       └── route.ts
│   │   │   ├── suppliers/
│   │   │   │   ├── route.ts
│   │   │   │   └── [id]/
│   │   │   │       └── route.ts
│   │   │   └── reports/
│   │   │       └── route.ts
│   │   └── webhooks/
│   │       ├── stripe/
│   │       │   └── route.ts
│   │       └── twilio/
│   │           └── route.ts
│   ├── globals.css
│   ├── layout.tsx
│   ├── page.tsx
│   ├── loading.tsx
│   ├── error.tsx
│   ├── not-found.tsx
│   └── robots.ts
├── components/
│   ├── ui/
│   │   ├── button.tsx
│   │   ├── input.tsx
│   │   ├── table.tsx
│   │   ├── card.tsx
│   │   ├── dialog.tsx
│   │   ├── form.tsx
│   │   ├── sidebar.tsx
│   │   ├── navbar.tsx
│   │   ├── badge.tsx
│   │   ├── alert.tsx
│   │   ├── toast.tsx
│   │   ├── select.tsx
│   │   ├── tabs.tsx
│   │   ├── chart.tsx
│   │   ├── data-table.tsx
│   │   ├── breadcrumb.tsx
│   │   ├── pagination.tsx
│   │   ├── sheet.tsx
│   │   └── ... (all Shadcn components)
│   ├── admin/
│   │   ├── layout/
│   │   │   ├── admin-sidebar.tsx
│   │   │   ├── admin-navbar.tsx
│   │   │   └── admin-sidebar-nav.tsx
│   │   ├── dashboard/
│   │   │   ├── admin-stats-cards.tsx
│   │   │   ├── system-health.tsx
│   │   │   ├── recent-activities.tsx
│   │   │   └── user-growth-chart.tsx
│   │   ├── users/
│   │   │   ├── users-table.tsx
│   │   │   ├── user-form.tsx
│   │   │   ├── user-details.tsx
│   │   │   ├── role-management.tsx
│   │   │   └── permissions-editor.tsx
│   │   ├── pharmacies/
│   │   │   ├── pharmacies-table.tsx
│   │   │   ├── pharmacy-form.tsx
│   │   │   └── pharmacy-selector.tsx
│   │   └── system/
│   │       ├── settings-form.tsx
│   │       ├── audit-logs-table.tsx
│   │       ├── backup-manager.tsx
│   │       └── notification-settings.tsx
│   ├── dashboard/
│   │   ├── layout/
│   │   │   ├── dashboard-sidebar.tsx
│   │   │   ├── dashboard-navbar.tsx
│   │   │   └── sidebar-nav.tsx
│   │   ├── overview/
│   │   │   ├── stats-cards.tsx
│   │   │   ├── recent-sales.tsx
│   │   │   ├── low-stock-alerts.tsx
│   │   │   └── quick-actions.tsx
│   │   └── widgets/
│   │       ├── expiry-alerts.tsx
│   │       ├── prescription-queue.tsx
│   │       └── sales-trend.tsx
│   ├── inventory/
│   │   ├── drug-table.tsx
│   │   ├── drug-form.tsx
│   │   ├── drug-details.tsx
│   │   ├── stock-alerts.tsx
│   │   ├── batch-management.tsx
│   │   ├── categories-manager.tsx
│   │   └── inventory-search.tsx
│   ├── patients/
│   │   ├── patient-table.tsx
│   │   ├── patient-form.tsx
│   │   ├── patient-details.tsx
│   │   ├── medical-history.tsx
│   │   ├── patient-groups.tsx
│   │   └── patient-search.tsx
│   ├── sales/
│   │   ├── pos-interface.tsx
│   │   ├── cart-items.tsx
│   │   ├── billing-form.tsx
│   │   ├── invoice-template.tsx
│   │   ├── return-form.tsx
│   │   └── payment-processor.tsx
│   ├── prescriptions/
│   │   ├── prescription-form.tsx
│   │   ├── prescription-view.tsx
│   │   ├── drug-search.tsx
│   │   ├── prescription-queue.tsx
│   │   └── prescription-validator.tsx
│   ├── suppliers/
│   │   ├── suppliers-table.tsx
│   │   ├── supplier-form.tsx
│   │   ├── purchase-orders.tsx
│   │   └── order-form.tsx
│   ├── reports/
│   │   ├── sales-chart.tsx
│   │   ├── inventory-report.tsx
│   │   ├── financial-summary.tsx
│   │   ├── custom-report-builder.tsx
│   │   └── report-export.tsx
│   └── shared/
│       ├── layout/
│       │   ├── header.tsx
│       │   ├── footer.tsx
│       │   └── breadcrumb.tsx
│       ├── forms/
│       │   ├── search-bar.tsx
│       │   ├── filter-dropdown.tsx
│       │   └── date-range-picker.tsx
│       ├── data/
│       │   ├── data-table.tsx
│       │   ├── pagination.tsx
│       │   └── sortable-header.tsx
│       ├── feedback/
│       │   ├── loading-spinner.tsx
│       │   ├── error-message.tsx
│       │   ├── empty-state.tsx
│       │   └── confirmation-dialog.tsx
│       ├── auth/
│       │   ├── protected-route.tsx
│       │   ├── role-guard.tsx
│       │   └── permission-wrapper.tsx
│       └── utils/
│           ├── file-upload.tsx
│           ├── print-button.tsx
│           └── export-button.tsx
├── lib/
│   ├── auth/
│   │   ├── auth.ts
│   │   ├── options.ts
│   │   ├── session.ts
│   │   └── providers.ts
│   ├── db/
│   │   ├── index.ts
│   │   ├── schema/
│   │   │   ├── users.ts
│   │   │   ├── inventory.ts
│   │   │   ├── patients.ts
│   │   │   ├── sales.ts
│   │   │   └── prescriptions.ts
│   │   ├── queries/
│   │   │   ├── users.ts
│   │   │   ├── inventory.ts
│   │   │   ├── patients.ts
│   │   │   ├── sales.ts
│   │   │   └── prescriptions.ts
│   │   └── migrations/
│   ├── api/
│   │   ├── client.ts
│   │   ├── endpoints.ts
│   │   ├── middleware.ts
│   │   └── error-handler.ts
│   ├── utils/
│   │   ├── index.ts
│   │   ├── formatters.ts
│   │   ├── validators.ts
│   │   ├── calculations.ts
│   │   └── helpers.ts
│   ├── validations/
│   │   ├── auth.ts
│   │   ├── inventory.ts
│   │   ├── patients.ts
│   │   ├── sales.ts
│   │   └── prescriptions.ts
│   ├── constants/
│   │   ├── roles.ts
│   │   ├── permissions.ts
│   │   ├── routes.ts
│   │   └── drug-categories.ts
│   ├── hooks/
│   │   ├── use-debounce.ts
│   │   ├── use-local-storage.ts
│   │   ├── use-query-string.ts
│   │   └── use-media-query.ts
│   └── types/
│       ├── database.types.ts
│       ├── api.types.ts
│       └── common.types.ts
├── hooks/
│   ├── auth/
│   │   ├── use-auth.ts
│   │   ├── use-session.ts
│   │   └── use-permissions.ts
│   ├── data/
│   │   ├── use-inventory.ts
│   │   ├── use-patients.ts
│   │   ├── use-sales.ts
│   │   ├── use-prescriptions.ts
│   │   └── use-suppliers.ts
│   ├── ui/
│   │   ├── use-toast.ts
│   │   ├── use-theme.ts
│   │   ├── use-sidebar.ts
│   │   └── use-mobile.ts
│   └── utils/
│       ├── use-debounce.ts
│       ├── use-local-storage.ts
│       └── use-query-string.ts
├── store/
│   ├── index.ts
│   ├── auth-store.ts
│   ├── ui-store.ts
│   ├── inventory-store.ts
│   ├── patient-store.ts
│   └── sales-store.ts
├── types/
│   ├── auth.ts
│   ├── inventory.ts
│   ├── patient.ts
│   ├── sale.ts
│   ├── prescription.ts
│   ├── supplier.ts
│   ├── user.ts
│   ├── pharmacy.ts
│   ├── api.ts
│   └── index.ts
├── utils/
│   ├── formatters/
│   │   ├── currency.ts
│   │   ├── date.ts
│   │   ├── string.ts
│   │   └── phone.ts
│   ├── validators/
│   │   ├── drug-validator.ts
│   │   ├── prescription-validator.ts
│   │   └── patient-validator.ts
│   ├── calculations/
│   │   ├── pricing.ts
│   │   ├── inventory.ts
│   │   └── sales.ts
│   ├── exports/
│   │   ├── csv-exporter.ts
│   │   ├── pdf-exporter.ts
│   │   └── excel-exporter.ts
│   └── imports/
│       ├── csv-importer.ts
│       └── data-validator.ts
├── config/
│   ├── site.ts
│   ├── database.ts
│   ├── auth.ts
│   ├── api.ts
│   ├── storage.ts
│   └── features.ts
├── middleware/
│   ├── auth.ts
│   ├── rate-limit.ts
│   ├── cors.ts
│   └── audit.ts
├── scripts/
│   ├── db/
│   │   ├── seed.ts
│   │   ├── migrate.ts
│   │   └── backup.ts
│   ├── deployment/
│   │   ├── build.ts
│   │   ├── test.ts
│   │   └── deploy.ts
│   └── maintenance/
│       ├── cleanup.ts
│       └── analytics.ts
├── public/
│   ├── assets/
│   │   ├── images/
│   │   │   ├── logo.png
│   │   │   ├── favicon.ico
│   │   │   └── placeholder-drug.jpg
│   │   └── icons/
│   ├── templates/
│   │   ├── import-drugs.csv
│   │   ├── import-patients.csv
│   │   └── inventory-template.xlsx
│   └── docs/
│       ├── user-manual.pdf
│       └── api-documentation.pdf
├── tests/
│   ├── unit/
│   │   ├── utils/
│   │   ├── components/
│   │   └── hooks/
│   ├── integration/
│   │   ├── api/
│   │   └── auth/
│   ├── e2e/
│   │   ├── inventory.spec.ts
│   │   ├── sales.spec.ts
│   │   └── prescriptions.spec.ts
│   └── fixtures/
│       ├── test-data.ts
│       └── mocks.ts
├── docs/
│   ├── api/
│   │   ├── endpoints.md
│   │   └── authentication.md
│   ├── deployment/
│   │   ├── setup.md
│   │   ├── environment.md
│   │   └── production.md
│   └── development/
│       ├── contributing.md
│       ├── architecture.md
│       └── coding-standards.md
├── .env.local
├── .env.production
├── .env.development
├── .eslintrc.json
├── .prettierrc
├── tailwind.config.ts
├── next.config.ts
├── tsconfig.json
├── package.json
└── README.md
```