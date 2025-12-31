# rules-us-fl

Florida rules encoded in Akoma Ntoso XML format for use in the Cosilico ecosystem.

## Structure

```
rules-us-fl/
├── statutes/                    # Florida Statutes
│   ├── title-14-taxation/       # Title XIV - Taxation and Finance
│   └── title-30-social-welfare/ # Title XXX - Social Welfare
└── regulations/                 # Florida Administrative Code (FAC)
```

## Sources

- **Florida Statutes**: http://www.leg.state.fl.us/statutes/
- **Florida Administrative Code**: https://www.flrules.org/

## Format

All rules are encoded in [Akoma Ntoso](http://www.akomantoso.org/) XML format, the OASIS standard for legal documents.

## Related Repositories

- [rac](https://github.com/CosilicoAI/rac) - Rules as Code DSL
- [arch](https://github.com/CosilicoAI/arch) - Source document archive
- [rules-us](https://github.com/CosilicoAI/rules-us) - US federal rules

## License

The underlying Florida Statutes and Administrative Code are public domain. The Akoma Ntoso encodings in this repository are released under the MIT License.
