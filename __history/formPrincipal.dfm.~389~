object frmPrincipal: TfrmPrincipal
  Left = 0
  Top = 0
  Caption = 'Migrador CSV'
  ClientHeight = 780
  ClientWidth = 1045
  Color = clBtnFace
  Font.Charset = DEFAULT_CHARSET
  Font.Color = clWindowText
  Font.Height = -11
  Font.Name = 'Tahoma'
  Font.Style = []
  KeyPreview = True
  OldCreateOrder = False
  Position = poScreenCenter
  OnClose = FormClose
  OnKeyPress = FormKeyPress
  DesignSize = (
    1045
    780)
  PixelsPerInch = 96
  TextHeight = 13
  object Panel1: TPanel
    Left = 0
    Top = 0
    Width = 1045
    Height = 193
    Align = alTop
    TabOrder = 0
    object Label1: TLabel
      Left = 164
      Top = 113
      Width = 58
      Height = 13
      Caption = 'Tabela CSV:'
    end
    object lblStatus: TLabel
      Left = 960
      Top = 174
      Width = 80
      Height = 13
      Caption = 'Desconectado'
      Font.Charset = DEFAULT_CHARSET
      Font.Color = clMaroon
      Font.Height = -11
      Font.Name = 'Tahoma'
      Font.Style = [fsBold]
      ParentFont = False
    end
    object Label3: TLabel
      Left = 4
      Top = 174
      Width = 56
      Height = 13
      Caption = 'Qtde Itens:'
    end
    object Label4: TLabel
      Left = 150
      Top = 174
      Width = 62
      Height = 13
      Caption = 'Qtde. Fields:'
    end
    object lblQtdeCol: TLabel
      Left = 218
      Top = 174
      Width = 6
      Height = 13
      Caption = '0'
      Font.Charset = DEFAULT_CHARSET
      Font.Color = clRed
      Font.Height = -11
      Font.Name = 'Tahoma'
      Font.Style = []
      ParentFont = False
    end
    object lblQtdeItens: TLabel
      Left = 66
      Top = 174
      Width = 6
      Height = 13
      Caption = '0'
      Font.Charset = DEFAULT_CHARSET
      Font.Color = clRed
      Font.Height = -11
      Font.Name = 'Tahoma'
      Font.Style = []
      ParentFont = False
    end
    object Label2: TLabel
      Left = 921
      Top = 174
      Width = 35
      Height = 13
      Caption = 'Status:'
      Font.Charset = DEFAULT_CHARSET
      Font.Color = clBlack
      Font.Height = -11
      Font.Name = 'Tahoma'
      Font.Style = []
      ParentFont = False
    end
    object Image1: TImage
      Left = 14
      Top = 62
      Width = 143
      Height = 87
      Proportional = True
      Stretch = True
    end
    object btnAbrirCSV: TButton
      Left = 627
      Top = 126
      Width = 75
      Height = 25
      Caption = 'Abrir'
      TabOrder = 7
      OnClick = btnAbrirCSVClick
    end
    object edtTabelaCSV: TEdit
      Left = 163
      Top = 128
      Width = 458
      Height = 21
      TabOrder = 6
    end
    object edtServer: TLabeledEdit
      Left = 163
      Top = 31
      Width = 184
      Height = 21
      EditLabel.Width = 32
      EditLabel.Height = 13
      EditLabel.Caption = 'Server'
      TabOrder = 0
      OnClick = edtServerClick
    end
    object edtBD: TLabeledEdit
      Left = 353
      Top = 31
      Width = 361
      Height = 21
      EditLabel.Width = 77
      EditLabel.Height = 13
      EditLabel.Caption = 'Banco de Dados'
      TabOrder = 1
      OnClick = edtBDClick
    end
    object edtUsuario: TLabeledEdit
      Left = 163
      Top = 70
      Width = 184
      Height = 21
      EditLabel.Width = 36
      EditLabel.Height = 13
      EditLabel.Caption = 'Usu'#225'rio'
      TabOrder = 2
      OnClick = edtUsuarioClick
    end
    object edtSenha: TLabeledEdit
      Left = 353
      Top = 70
      Width = 184
      Height = 21
      EditLabel.Width = 30
      EditLabel.Height = 13
      EditLabel.Caption = 'Senha'
      PasswordChar = '*'
      TabOrder = 3
      OnClick = edtSenhaClick
    end
    object btnAbreBanco: TButton
      Left = 726
      Top = 29
      Width = 75
      Height = 25
      Caption = 'Conectar'
      TabOrder = 4
      OnClick = btnAbreBancoClick
    end
    object btnLimpar: TButton
      Left = 708
      Top = 126
      Width = 75
      Height = 25
      Caption = 'Limpar'
      TabOrder = 8
      OnClick = btnLimparClick
    end
    object btnDesconectar: TButton
      Left = 810
      Top = 29
      Width = 75
      Height = 25
      Caption = 'Desconectar'
      TabOrder = 5
      OnClick = btnDesconectarClick
    end
    object ckMostraSenha: TCheckBox
      Left = 543
      Top = 70
      Width = 97
      Height = 17
      Caption = 'Mostrar senha'
      TabOrder = 9
      OnClick = ckMostraSenhaClick
    end
  end
  object DBGrid1: TDBGrid
    Left = 0
    Top = 193
    Width = 1045
    Height = 357
    Align = alClient
    DataSource = dsTab
    ReadOnly = True
    TabOrder = 1
    TitleFont.Charset = DEFAULT_CHARSET
    TitleFont.Color = clWindowText
    TitleFont.Height = -11
    TitleFont.Name = 'Tahoma'
    TitleFont.Style = []
    Columns = <
      item
        Expanded = False
        FieldName = 'Cod'
        Visible = True
      end
      item
        Expanded = False
        FieldName = 'Campo'
        Visible = True
      end>
  end
  object PnProgresso: TPanel
    Left = 326
    Top = 322
    Width = 388
    Height = 58
    Anchors = []
    TabOrder = 3
    Visible = False
    object lblexec: TLabel
      Left = 14
      Top = 7
      Width = 57
      Height = 13
      Caption = 'Executando'
    end
    object PbProgresso: TProgressBar
      Left = 14
      Top = 26
      Width = 361
      Height = 17
      TabOrder = 0
    end
  end
  object PageControl1: TPageControl
    Left = 0
    Top = 550
    Width = 1045
    Height = 230
    ActivePage = TabSocios
    Align = alBottom
    TabOrder = 2
    object TabSocios: TTabSheet
      Caption = 'S'#243'cios'
      object btnMigraSocios: TButton
        Left = 16
        Top = 164
        Width = 75
        Height = 25
        Caption = 'Migrar'
        TabOrder = 26
        OnClick = btnMigraSociosClick
      end
      object ckSocio_AutoInc: TCheckBox
        Left = 97
        Top = 168
        Width = 149
        Height = 17
        Caption = 'Matricula -> Gerar AutoInc'
        TabOrder = 27
        OnClick = ckSocio_AutoIncClick
      end
      object pSocioMatricula: TLabeledEdit
        Left = 16
        Top = 38
        Width = 75
        Height = 21
        EditLabel.Width = 43
        EditLabel.Height = 13
        EditLabel.Caption = 'Matricula'
        NumbersOnly = True
        TabOrder = 0
      end
      object pSocioNome: TLabeledEdit
        Left = 184
        Top = 38
        Width = 75
        Height = 21
        EditLabel.Width = 27
        EditLabel.Height = 13
        EditLabel.Caption = 'Nome'
        TabOrder = 2
      end
      object pSocioTelefones: TLabeledEdit
        Left = 16
        Top = 86
        Width = 75
        Height = 21
        EditLabel.Width = 47
        EditLabel.Height = 13
        EditLabel.Caption = 'Telefones'
        TabOrder = 12
      end
      object pSociosNascimento: TLabeledEdit
        Left = 100
        Top = 86
        Width = 75
        Height = 21
        EditLabel.Width = 55
        EditLabel.Height = 13
        EditLabel.Caption = 'Nascimento'
        TabOrder = 13
      end
      object pSocioProfissao: TLabeledEdit
        Left = 184
        Top = 86
        Width = 75
        Height = 21
        EditLabel.Width = 44
        EditLabel.Height = 13
        EditLabel.Caption = 'Profiss'#227'o'
        TabOrder = 14
      end
      object pSocioCTPSN: TLabeledEdit
        Left = 268
        Top = 86
        Width = 75
        Height = 21
        EditLabel.Width = 32
        EditLabel.Height = 13
        EditLabel.Caption = 'CTPSN'
        TabOrder = 15
      end
      object pSocioCTPSS: TLabeledEdit
        Left = 352
        Top = 86
        Width = 75
        Height = 21
        EditLabel.Width = 31
        EditLabel.Height = 13
        EditLabel.Caption = 'CTPSS'
        TabOrder = 16
      end
      object pSocioEndereco: TLabeledEdit
        Left = 268
        Top = 38
        Width = 75
        Height = 21
        EditLabel.Width = 45
        EditLabel.Height = 13
        EditLabel.Caption = 'Endereco'
        TabOrder = 3
      end
      object pSocioNumero: TLabeledEdit
        Left = 352
        Top = 38
        Width = 75
        Height = 21
        EditLabel.Width = 37
        EditLabel.Height = 13
        EditLabel.Caption = 'Numero'
        TabOrder = 4
      end
      object pSocioBairro: TLabeledEdit
        Left = 436
        Top = 38
        Width = 75
        Height = 21
        EditLabel.Width = 28
        EditLabel.Height = 13
        EditLabel.Caption = 'Bairro'
        TabOrder = 5
      end
      object pSocioEmpAtual: TLabeledEdit
        Left = 436
        Top = 86
        Width = 75
        Height = 21
        EditLabel.Width = 69
        EditLabel.Height = 13
        EditLabel.Caption = 'Empresa Atual'
        TabOrder = 17
      end
      object pSocioCidade: TLabeledEdit
        Left = 520
        Top = 38
        Width = 75
        Height = 21
        EditLabel.Width = 33
        EditLabel.Height = 13
        EditLabel.Caption = 'Cidade'
        TabOrder = 6
      end
      object pSocioSexo: TLabeledEdit
        Left = 520
        Top = 86
        Width = 75
        Height = 21
        EditLabel.Width = 24
        EditLabel.Height = 13
        EditLabel.Caption = 'Sexo'
        TabOrder = 18
      end
      object pSocioRG: TLabeledEdit
        Left = 604
        Top = 86
        Width = 75
        Height = 21
        EditLabel.Width = 14
        EditLabel.Height = 13
        EditLabel.Caption = 'RG'
        TabOrder = 19
      end
      object pSocioCPF: TLabeledEdit
        Left = 688
        Top = 86
        Width = 75
        Height = 21
        EditLabel.Width = 19
        EditLabel.Height = 13
        EditLabel.Caption = 'CPF'
        TabOrder = 20
      end
      object pSocioComplemento: TLabeledEdit
        Left = 604
        Top = 38
        Width = 75
        Height = 21
        EditLabel.Width = 65
        EditLabel.Height = 13
        EditLabel.Caption = 'Complemento'
        TabOrder = 7
      end
      object pSocioUF: TLabeledEdit
        Left = 688
        Top = 38
        Width = 75
        Height = 21
        EditLabel.Width = 13
        EditLabel.Height = 13
        EditLabel.Caption = 'UF'
        TabOrder = 8
      end
      object pSocioCEP: TLabeledEdit
        Left = 772
        Top = 38
        Width = 75
        Height = 21
        EditLabel.Width = 19
        EditLabel.Height = 13
        EditLabel.Caption = 'CEP'
        TabOrder = 9
      end
      object pSocioEmail: TLabeledEdit
        Left = 772
        Top = 86
        Width = 75
        Height = 21
        EditLabel.Width = 28
        EditLabel.Height = 13
        EditLabel.Caption = 'E-mail'
        TabOrder = 21
      end
      object pSocioNatural: TLabeledEdit
        Left = 856
        Top = 38
        Width = 75
        Height = 21
        EditLabel.Width = 61
        EditLabel.Height = 13
        EditLabel.Caption = 'Naturalidade'
        TabOrder = 10
      end
      object pSocioSalario: TLabeledEdit
        Left = 856
        Top = 86
        Width = 75
        Height = 21
        EditLabel.Width = 32
        EditLabel.Height = 13
        EditLabel.Caption = 'Sal'#225'rio'
        TabOrder = 22
      end
      object pSocioPIS: TLabeledEdit
        Left = 940
        Top = 86
        Width = 75
        Height = 21
        EditLabel.Width = 16
        EditLabel.Height = 13
        EditLabel.Caption = 'PIS'
        TabOrder = 23
      end
      object pSocioEstado: TLabeledEdit
        Left = 940
        Top = 38
        Width = 75
        Height = 21
        EditLabel.Width = 55
        EditLabel.Height = 13
        EditLabel.Caption = 'Estado Civil'
        TabOrder = 11
      end
      object pSocioCodSede: TLabeledEdit
        Left = 100
        Top = 38
        Width = 75
        Height = 21
        EditLabel.Width = 50
        EditLabel.Height = 13
        EditLabel.Caption = 'Cod. Sede'
        TabOrder = 1
      end
      object pSocioMae: TLabeledEdit
        Left = 16
        Top = 126
        Width = 75
        Height = 21
        EditLabel.Width = 65
        EditLabel.Height = 13
        EditLabel.Caption = 'Nome da M'#227'e'
        TabOrder = 24
      end
      object pSocioPai: TLabeledEdit
        Left = 100
        Top = 126
        Width = 75
        Height = 21
        EditLabel.Width = 59
        EditLabel.Height = 13
        EditLabel.Caption = 'Nome da Pai'
        TabOrder = 25
      end
    end
    object tabEmpresas: TTabSheet
      Caption = 'Empresas'
      ImageIndex = 2
      object btnMigraEmpresas: TButton
        Left = 671
        Top = 151
        Width = 75
        Height = 25
        Caption = 'Migrar'
        TabOrder = 22
        OnClick = btnMigraEmpresasClick
      end
      object pEmpresaCod: TLabeledEdit
        Left = 19
        Top = 28
        Width = 80
        Height = 21
        EditLabel.Width = 33
        EditLabel.Height = 13
        EditLabel.Caption = 'Codigo'
        TabOrder = 0
      end
      object pEmpresaNome: TLabeledEdit
        Left = 197
        Top = 28
        Width = 80
        Height = 21
        EditLabel.Width = 27
        EditLabel.Height = 13
        EditLabel.Caption = 'Nome'
        TabOrder = 2
      end
      object pEmpresaEnd: TLabeledEdit
        Left = 19
        Top = 76
        Width = 80
        Height = 21
        EditLabel.Width = 45
        EditLabel.Height = 13
        EditLabel.Caption = 'Endere'#231'o'
        TabOrder = 10
      end
      object pEmpresaCNPJ: TLabeledEdit
        Left = 464
        Top = 28
        Width = 80
        Height = 21
        EditLabel.Width = 25
        EditLabel.Height = 13
        EditLabel.Caption = 'CNPJ'
        TabOrder = 5
      end
      object pEmpresaTel: TLabeledEdit
        Left = 642
        Top = 76
        Width = 80
        Height = 21
        EditLabel.Width = 47
        EditLabel.Height = 13
        EditLabel.Caption = 'Telefones'
        TabOrder = 17
      end
      object pEmpresaComplemento: TLabeledEdit
        Left = 197
        Top = 76
        Width = 80
        Height = 21
        EditLabel.Width = 65
        EditLabel.Height = 13
        EditLabel.Caption = 'Complemento'
        TabOrder = 12
      end
      object pEmpresaBairro: TLabeledEdit
        Left = 286
        Top = 76
        Width = 80
        Height = 21
        EditLabel.Width = 28
        EditLabel.Height = 13
        EditLabel.Caption = 'Bairro'
        TabOrder = 13
      end
      object pEmpresaCidade: TLabeledEdit
        Left = 375
        Top = 76
        Width = 80
        Height = 21
        EditLabel.Width = 33
        EditLabel.Height = 13
        EditLabel.Caption = 'Cidade'
        TabOrder = 14
      end
      object pEmpresaUF: TLabeledEdit
        Left = 464
        Top = 76
        Width = 80
        Height = 21
        EditLabel.Width = 13
        EditLabel.Height = 13
        EditLabel.Caption = 'UF'
        TabOrder = 15
      end
      object pEmpresaNomeFant: TLabeledEdit
        Left = 286
        Top = 27
        Width = 80
        Height = 21
        EditLabel.Width = 71
        EditLabel.Height = 13
        EditLabel.Caption = 'Nome Fantasia'
        TabOrder = 3
      end
      object pEmpresaGrupo: TLabeledEdit
        Left = 375
        Top = 28
        Width = 80
        Height = 21
        EditLabel.Width = 29
        EditLabel.Height = 13
        EditLabel.Caption = 'Grupo'
        TabOrder = 4
      end
      object pEmpresaCNAE: TLabeledEdit
        Left = 553
        Top = 28
        Width = 80
        Height = 21
        EditLabel.Width = 27
        EditLabel.Height = 13
        EditLabel.Caption = 'CNAE'
        TabOrder = 6
      end
      object pEmpresaContato: TLabeledEdit
        Left = 730
        Top = 76
        Width = 80
        Height = 21
        EditLabel.Width = 39
        EditLabel.Height = 13
        EditLabel.Caption = 'Contato'
        TabOrder = 18
      end
      object pEmpresaEmail: TLabeledEdit
        Left = 820
        Top = 76
        Width = 80
        Height = 21
        EditLabel.Width = 28
        EditLabel.Height = 13
        EditLabel.Caption = 'E-Mail'
        TabOrder = 19
      end
      object pEmpresaTipo: TLabeledEdit
        Left = 820
        Top = 28
        Width = 80
        Height = 21
        EditLabel.Width = 20
        EditLabel.Height = 13
        EditLabel.Caption = 'Tipo'
        TabOrder = 9
      end
      object pEmpresaNum: TLabeledEdit
        Left = 108
        Top = 76
        Width = 80
        Height = 21
        EditLabel.Width = 37
        EditLabel.Height = 13
        EditLabel.Caption = 'Numero'
        TabOrder = 11
      end
      object pEmpresaCEP: TLabeledEdit
        Left = 553
        Top = 76
        Width = 80
        Height = 21
        EditLabel.Width = 19
        EditLabel.Height = 13
        EditLabel.Caption = 'CEP'
        TabOrder = 16
      end
      object pEmpresaDescCNAE: TLabeledEdit
        Left = 642
        Top = 28
        Width = 80
        Height = 21
        EditLabel.Width = 57
        EditLabel.Height = 13
        EditLabel.Caption = 'Desc. CNAE'
        TabOrder = 7
      end
      object pEmpresaQtdeFunc: TLabeledEdit
        Left = 731
        Top = 28
        Width = 80
        Height = 21
        EditLabel.Width = 58
        EditLabel.Height = 13
        EditLabel.Caption = 'Qtde. Func.'
        TabOrder = 8
      end
      object GroupBox1: TGroupBox
        Left = 19
        Top = 103
        Width = 646
        Height = 82
        Caption = 'Endere'#231'o de Cobran'#231'a'
        TabOrder = 20
        object pEmpresaCobEnd: TLabeledEdit
          Left = 15
          Top = 41
          Width = 80
          Height = 21
          EditLabel.Width = 45
          EditLabel.Height = 13
          EditLabel.Caption = 'Endere'#231'o'
          TabOrder = 0
        end
        object pEmpresaCobNum: TLabeledEdit
          Left = 104
          Top = 41
          Width = 80
          Height = 21
          EditLabel.Width = 37
          EditLabel.Height = 13
          EditLabel.Caption = 'Numero'
          TabOrder = 1
        end
        object pEmpresaCobComp: TLabeledEdit
          Left = 193
          Top = 41
          Width = 80
          Height = 21
          EditLabel.Width = 65
          EditLabel.Height = 13
          EditLabel.Caption = 'Complemento'
          TabOrder = 2
        end
        object pEmpresaCobBairro: TLabeledEdit
          Left = 282
          Top = 41
          Width = 80
          Height = 21
          EditLabel.Width = 28
          EditLabel.Height = 13
          EditLabel.Caption = 'Bairro'
          TabOrder = 3
        end
        object pEmpresaCobCidade: TLabeledEdit
          Left = 371
          Top = 41
          Width = 80
          Height = 21
          EditLabel.Width = 33
          EditLabel.Height = 13
          EditLabel.Caption = 'Cidade'
          TabOrder = 4
        end
        object pEmpresaCobUF: TLabeledEdit
          Left = 460
          Top = 41
          Width = 80
          Height = 21
          EditLabel.Width = 13
          EditLabel.Height = 13
          EditLabel.Caption = 'UF'
          TabOrder = 5
        end
        object pEmpresaCobEndCEP: TLabeledEdit
          Left = 549
          Top = 41
          Width = 80
          Height = 21
          EditLabel.Width = 19
          EditLabel.Height = 13
          EditLabel.Caption = 'CEP'
          TabOrder = 6
        end
      end
      object ckEmpresa_AutoInc: TCheckBox
        Left = 671
        Top = 112
        Width = 149
        Height = 17
        Caption = 'Codigo -> Gerar AutoInc'
        TabOrder = 21
        OnClick = ckEmpresa_AutoIncClick
      end
      object pEmpresaSede: TLabeledEdit
        Left = 111
        Top = 28
        Width = 80
        Height = 21
        EditLabel.Width = 50
        EditLabel.Height = 13
        EditLabel.Caption = 'Cod. Sede'
        TabOrder = 1
      end
    end
    object tabHomologacao: TTabSheet
      Caption = 'Homologa'#231#227'o'
      ImageIndex = 5
      object Button1: TButton
        Left = 11
        Top = 156
        Width = 75
        Height = 25
        Caption = 'Migrar'
        TabOrder = 11
        OnClick = hhfhf
      end
      object ckHomologacao_AutoInc: TCheckBox
        Left = 92
        Top = 160
        Width = 149
        Height = 17
        Caption = 'CodInt -> Gerar AutoInc'
        TabOrder = 12
        OnClick = ckSocio_AutoIncClick
      end
      object pHomologacaoCodInt: TLabeledEdit
        Left = 11
        Top = 44
        Width = 75
        Height = 21
        EditLabel.Width = 33
        EditLabel.Height = 13
        EditLabel.Caption = 'CodInt'
        NumbersOnly = True
        TabOrder = 0
      end
      object pHomologacaoData: TLabeledEdit
        Left = 92
        Top = 92
        Width = 75
        Height = 21
        EditLabel.Width = 23
        EditLabel.Height = 13
        EditLabel.Caption = 'Data'
        TabOrder = 2
      end
      object pHomologacaoHora: TLabeledEdit
        Left = 176
        Top = 92
        Width = 75
        Height = 21
        EditLabel.Width = 23
        EditLabel.Height = 13
        EditLabel.Caption = 'Hora'
        TabOrder = 3
      end
      object pHomologacaoCodSocio: TLabeledEdit
        Left = 355
        Top = 44
        Width = 75
        Height = 21
        EditLabel.Width = 51
        EditLabel.Height = 13
        EditLabel.Caption = 'Cod. S'#243'cio'
        TabOrder = 4
      end
      object pHomologacaoDataAdm: TLabeledEdit
        Left = 517
        Top = 44
        Width = 75
        Height = 21
        EditLabel.Width = 71
        EditLabel.Height = 13
        EditLabel.Caption = 'Data Admiss'#227'o'
        TabOrder = 5
      end
      object pHomologacaoDataDemis: TLabeledEdit
        Left = 601
        Top = 44
        Width = 75
        Height = 21
        EditLabel.Width = 71
        EditLabel.Height = 13
        EditLabel.Caption = 'Data Demiss'#227'o'
        TabOrder = 6
      end
      object pHomologacaoUltSal: TLabeledEdit
        Left = 685
        Top = 44
        Width = 75
        Height = 21
        EditLabel.Width = 64
        EditLabel.Height = 13
        EditLabel.Caption = 'Ultimo Sal'#225'rio'
        TabOrder = 7
      end
      object pHomologacaoNome: TLabeledEdit
        Left = 769
        Top = 44
        Width = 75
        Height = 21
        EditLabel.Width = 27
        EditLabel.Height = 13
        EditLabel.Caption = 'Nome'
        TabOrder = 8
      end
      object pHomologacaoSexo: TLabeledEdit
        Left = 853
        Top = 44
        Width = 75
        Height = 21
        EditLabel.Width = 24
        EditLabel.Height = 13
        EditLabel.Caption = 'Sexo'
        TabOrder = 9
      end
      object pHomologacaoCidade: TLabeledEdit
        Left = 11
        Top = 92
        Width = 75
        Height = 21
        EditLabel.Width = 33
        EditLabel.Height = 13
        EditLabel.Caption = 'Cidade'
        TabOrder = 10
      end
      object pHomologacaoCodSede: TLabeledEdit
        Left = 95
        Top = 44
        Width = 75
        Height = 21
        EditLabel.Width = 50
        EditLabel.Height = 13
        EditLabel.Caption = 'Cod. Sede'
        TabOrder = 1
      end
      object pHomologacaoDataNasc: TLabeledEdit
        Left = 436
        Top = 44
        Width = 75
        Height = 21
        EditLabel.Width = 53
        EditLabel.Height = 13
        EditLabel.Caption = 'Data Nasc.'
        TabOrder = 13
      end
      object pHomologacaoCodHomo: TLabeledEdit
        Left = 176
        Top = 44
        Width = 75
        Height = 21
        EditLabel.Width = 89
        EditLabel.Height = 13
        EditLabel.Caption = 'Cod. Homologador'
        TabOrder = 14
      end
      object pHomologacaoCodEmp: TLabeledEdit
        Left = 274
        Top = 44
        Width = 75
        Height = 21
        EditLabel.Width = 67
        EditLabel.Height = 13
        EditLabel.Caption = 'Cod. Empresa'
        TabOrder = 15
      end
      object pHomologacaoObs: TLabeledEdit
        Left = 259
        Top = 92
        Width = 75
        Height = 21
        EditLabel.Width = 58
        EditLabel.Height = 13
        EditLabel.Caption = 'Observa'#231#227'o'
        TabOrder = 16
      end
      object pHomologacaoObsEmp: TLabeledEdit
        Left = 340
        Top = 92
        Width = 75
        Height = 21
        EditLabel.Width = 67
        EditLabel.Height = 13
        EditLabel.Caption = 'Obs. Empresa'
        TabOrder = 17
      end
      object pHomologacaoObsPub: TLabeledEdit
        Left = 421
        Top = 92
        Width = 75
        Height = 21
        EditLabel.Width = 64
        EditLabel.Height = 13
        EditLabel.Caption = 'Obs. P'#250'blicas'
        TabOrder = 18
      end
    end
    object tabDependentes: TTabSheet
      Caption = 'Depdendentes'
      ImageIndex = 1
      object btnMProd: TButton
        Left = 14
        Top = 165
        Width = 75
        Height = 25
        Caption = 'Migrar'
        TabOrder = 10
        OnClick = btnMProdClick
      end
      object pDependenteMatricula: TLabeledEdit
        Left = 14
        Top = 73
        Width = 75
        Height = 21
        EditLabel.Width = 43
        EditLabel.Height = 13
        EditLabel.Caption = 'Matricula'
        NumbersOnly = True
        TabOrder = 0
      end
      object pDependenteCodigo: TLabeledEdit
        Left = 176
        Top = 73
        Width = 75
        Height = 21
        EditLabel.Width = 33
        EditLabel.Height = 13
        EditLabel.Caption = 'Codigo'
        TabOrder = 2
      end
      object pDependenteNome: TLabeledEdit
        Left = 260
        Top = 73
        Width = 75
        Height = 21
        EditLabel.Width = 27
        EditLabel.Height = 13
        EditLabel.Caption = 'Nome'
        TabOrder = 3
      end
      object pDependenteSexo: TLabeledEdit
        Left = 344
        Top = 73
        Width = 75
        Height = 21
        EditLabel.Width = 24
        EditLabel.Height = 13
        EditLabel.Caption = 'Sexo'
        TabOrder = 4
      end
      object pDependenteParentesco: TLabeledEdit
        Left = 428
        Top = 73
        Width = 75
        Height = 21
        EditLabel.Width = 54
        EditLabel.Height = 13
        EditLabel.Caption = 'Parentesco'
        TabOrder = 5
      end
      object pDependenteRG: TLabeledEdit
        Left = 515
        Top = 73
        Width = 75
        Height = 21
        EditLabel.Width = 14
        EditLabel.Height = 13
        EditLabel.Caption = 'RG'
        TabOrder = 6
      end
      object pDependenteCPF: TLabeledEdit
        Left = 596
        Top = 73
        Width = 75
        Height = 21
        EditLabel.Width = 19
        EditLabel.Height = 13
        EditLabel.Caption = 'CPF'
        TabOrder = 7
      end
      object ckDependentes_AutoInc: TCheckBox
        Left = 14
        Top = 119
        Width = 149
        Height = 17
        Caption = 'Codigo -> Gerar AutoInc'
        TabOrder = 9
        OnClick = ckDependentes_AutoIncClick
      end
      object ckDependenteMat_AutoInc: TCheckBox
        Left = 14
        Top = 100
        Width = 149
        Height = 17
        Caption = 'Matricula -> Gerar AutoInc'
        TabOrder = 8
        OnClick = ckDependenteMat_AutoIncClick
      end
      object pDependenteSede: TLabeledEdit
        Left = 95
        Top = 73
        Width = 75
        Height = 21
        EditLabel.Width = 50
        EditLabel.Height = 13
        EditLabel.Caption = 'Cod. Sede'
        TabOrder = 1
      end
    end
    object TabSheet1: TTabSheet
      Caption = 'SQL'
      ImageIndex = 4
      object memSQL: TMemo
        Left = 3
        Top = 3
        Width = 910
        Height = 196
        ScrollBars = ssBoth
        TabOrder = 0
      end
      object btnSQL_Limpar: TButton
        Left = 942
        Top = 102
        Width = 75
        Height = 25
        Caption = 'Limpar'
        TabOrder = 2
        OnClick = btnSQL_LimparClick
      end
      object btnSQL_Execute: TButton
        Left = 942
        Top = 71
        Width = 75
        Height = 25
        Caption = 'Execute'
        TabOrder = 1
        OnClick = btnSQL_ExecuteClick
      end
    end
    object tabErros: TTabSheet
      Caption = 'Erros'
      ImageIndex = 4
      object memErros: TMemo
        Left = 0
        Top = 0
        Width = 951
        Height = 202
        Align = alCustom
        ScrollBars = ssBoth
        TabOrder = 0
      end
      object btnLimparErros: TButton
        Left = 959
        Top = 87
        Width = 75
        Height = 25
        Caption = 'Limpar'
        TabOrder = 1
        OnClick = btnLimparErrosClick
      end
    end
  end
  object dsTab: TDataSource
    Left = 829
    Top = 423
  end
end
