### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ProductNoticesStore.ClearOldNotices | avg | 2ms | 18ms | 16ms | 950.32
| RoleStore.ChannelHigherScopedPermissions | avg | 23ms | 126ms | 103ms | 455.09
| UserStore.GetMany | avg | 64ms | 192ms | 128ms | 199.06
| UserStore.GetProfilesInChannel | avg | 30ms | 79ms | 49ms | 163.35
| PostStore.AnalyticsPostCount | avg | 5.302s | 10.773s | 5.471s | 103.18
| ChannelStore.CreateSidebarCategory | avg | 143ms | 264ms | 121ms | 84.58
| UserAccessTokenStore.GetByToken | avg | 59ms | 105ms | 46ms | 78.24
| TokenStore.Cleanup | avg | 20ms | 35ms | 15ms | 74.16
| PostStore.SetPostReminder | avg | 47ms | 77ms | 30ms | 64.10
| JobStore.GetNewestJobByStatusesAndType | avg | 51ms | 81ms | 30ms | 58.77
| StatusStore.SaveOrUpdate | avg | 109ms | 167ms | 58ms | 53.44
| CommandWebhookStore.Cleanup | avg | 20ms | 30ms | 10ms | 50.20
| PreferenceStore.DeleteCategoryAndName | avg | 29ms | 42ms | 13ms | 44.67
| UserStore.IsEmpty | avg | 21ms | 29ms | 8ms | 37.49
| UserStore.GetByUsername | avg | 73ms | 99ms | 26ms | 35.70
| PostAcknowledgementStore.GetForPost | avg | 48ms | 62ms | 14ms | 29.08
| GroupStore.GetByName | avg | 35ms | 45ms | 10ms | 28.24
| GroupStore.AdminRoleGroupsForSyncableMember | avg | 38ms | 48ms | 10ms | 26.19
| ChannelStore.GetPublicChannelsForTeam | avg | 87ms | 109ms | 22ms | 25.34
| ChannelStore.GetTeamChannels | avg | 138ms | 171ms | 33ms | 23.84
| ChannelStore.GetMemberCount | avg | 354ms | 434ms | 80ms | 22.62
| ChannelStore.SaveMember | avg | 195ms | 238ms | 43ms | 22.05
| UserStore.GetForLogin | avg | 42ms | 51ms | 9ms | 21.43
| ChannelStore.GetGuestCount | avg | 66ms | 80ms | 14ms | 21.20
| PreferenceStore.Save | avg | 36ms | 43ms | 7ms | 19.56
| PostStore.GetPosts | avg | 42ms | 50ms | 8ms | 19.13
| TeamStore.GetTeamsByUserId | avg | 53ms | 63ms | 10ms | 18.92
| StatusStore.Get | avg | 32ms | 38ms | 6ms | 18.73
| UserStore.GetAllProfilesInChannel | avg | 1.386s | 1.645s | 259ms | 18.69
| ChannelStore.GetByName | avg | 39ms | 46ms | 7ms | 18.01
| ChannelStore.SearchGroupChannels | avg | 84ms | 99ms | 15ms | 17.90
| TeamStore.GetAllPage | avg | 50ms | 59ms | 9ms | 17.83
| UserTermsOfServiceStore.GetByUser | avg | 51ms | 60ms | 9ms | 17.58
| UserStore.GetAllProfiles | avg | 47ms | 55ms | 8ms | 17.07
| JobStore.Save | avg | 18ms | 21ms | 3ms | 16.33
| ChannelStore.GetPinnedPostCount | avg | 63ms | 73ms | 10ms | 15.80
| PreferenceStore.GetAll | avg | 58ms | 67ms | 9ms | 15.47
| TeamStore.GetChannelUnreadsForAllTeams | avg | 52ms | 60ms | 8ms | 15.24
| StatusStore.GetByIds | avg | 70ms | 80ms | 10ms | 14.24
| JobStore.GetCountByStatusAndType | avg | 58ms | 66ms | 8ms | 13.69
| ThreadStore.GetThreadUnreadReplyCount | avg | 74ms | 84ms | 10ms | 13.49
| ThreadStore.GetTotalThreads | avg | 53ms | 60ms | 7ms | 13.31
| ThreadStore.GetTotalUnreadMentions | avg | 53ms | 60ms | 7ms | 13.29
| GroupStore.GetGroups | avg | 60ms | 68ms | 8ms | 13.23
| ThreadStore.GetTotalUnreadUrgentMentions | avg | 53ms | 60ms | 7ms | 13.11
| FileInfoStore.GetForPost | avg | 77ms | 87ms | 10ms | 13.04
| ChannelStore.GetFileCount | avg | 49ms | 55ms | 6ms | 12.35
| PostStore.GetEtag | avg | 73ms | 82ms | 9ms | 12.27
| PostPriorityStore.GetForPosts | avg | 106ms | 119ms | 13ms | 12.24
| ChannelStore.Autocomplete | avg | 361ms | 405ms | 44ms | 12.18
| PostAcknowledgementStore.GetForPosts | avg | 101ms | 113ms | 12ms | 11.89
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | avg | 60ms | 67ms | 7ms | 11.71
| UserStore.GetProfilesByUsernames | avg | 60ms | 67ms | 7ms | 11.61
| PostStore.GetPostsSince | avg | 113ms | 126ms | 13ms | 11.47
| SessionStore.GetSessionsWithActiveDeviceIds | avg | 53ms | 59ms | 6ms | 11.43
| ThreadStore.MarkAllAsReadByChannels | avg | 26ms | 29ms | 3ms | 11.40
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 124ms | 138ms | 14ms | 11.28
| PostStore.GetPostsBefore | avg | 71ms | 79ms | 8ms | 11.20
| ChannelStore.UpdateSidebarChannelsByPreferences | avg | 18ms | 20ms | 2ms | 11.10
| ThreadStore.GetThreadsForUser | avg | 83ms | 92ms | 9ms | 10.79
| ThreadStore.GetThreadForUser | avg | 95ms | 105ms | 10ms | 10.49
| UserStore.GetUnreadCount | avg | 58ms | 64ms | 6ms | 10.34
| TeamStore.Get | avg | 59ms | 65ms | 6ms | 10.10
| ChannelStore.GetMembersForUser | avg | 70ms | 77ms | 7ms | 9.98
| UserStore.AutocompleteUsersInChannel | avg | 574ms | 629ms | 55ms | 9.59
| WebhookStore.GetOutgoingByTeam | avg | 74ms | 81ms | 7ms | 9.40
| UserStore.Search | avg | 192ms | 210ms | 18ms | 9.38
| ThreadStore.GetMembershipForUser | avg | 65ms | 71ms | 6ms | 9.23
| LinkMetadataStore.Get | avg | 65ms | 71ms | 6ms | 9.19
| PostPersistentNotificationStore.GetSingle | avg | 66ms | 72ms | 6ms | 9.15
| PostStore.GetPostsByThread | avg | 66ms | 72ms | 6ms | 9.11
| ThreadStore.GetTeamsUnreadForUser | avg | 77ms | 84ms | 7ms | 9.08
| ChannelStore.GetMember | avg | 22ms | 24ms | 2ms | 9.07
| PreferenceStore.Get | avg | 67ms | 73ms | 6ms | 8.95
| ChannelStore.GetChannels | avg | 78ms | 85ms | 7ms | 8.95
| ReactionStore.GetForPost | avg | 79ms | 86ms | 7ms | 8.87
| ChannelStore.CreateInitialSidebarCategories | avg | 91ms | 99ms | 8ms | 8.80
| SessionStore.Save | avg | 58ms | 63ms | 5ms | 8.60
| PostStore.Get | avg | 133ms | 144ms | 11ms | 8.28
| PostStore.GetSingle | avg | 63ms | 68ms | 5ms | 7.99
| ChannelStore.AutocompleteInTeamForSearch | avg | 443ms | 478ms | 35ms | 7.90
| ThreadStore.GetThreadFollowers | avg | 66ms | 71ms | 5ms | 7.58
| UserStore.GetProfileByIds | avg | 53ms | 57ms | 4ms | 7.53
| TeamStore.SaveMember | avg | 133ms | 143ms | 10ms | 7.51
| ChannelStore.Get | avg | 94ms | 101ms | 7ms | 7.46
| ThreadStore.GetTotalUnreadThreads | avg | 54ms | 58ms | 4ms | 7.45
| TeamStore.GetByName | avg | 56ms | 60ms | 4ms | 7.18
| ChannelStore.GetMemberForPost | avg | 52ms | 55ms | 3ms | 5.77
| TeamStore.GetTeamsForUser | avg | 52ms | 55ms | 3ms | 5.74
| FileInfoStore.Get | avg | 57ms | 60ms | 3ms | 5.25
| JobStore.GetAllByStatus | avg | 75ms | 78ms | 3ms | 3.98
| JobStore.Get | avg | 76ms | 79ms | 3ms | 3.94
| ThreadStore.Get | avg | 81ms | 84ms | 3ms | 3.70
| ChannelStore.GetChannelsByUser | avg | 87ms | 90ms | 3ms | 3.46
| ChannelStore.GetMembers | avg | 419ms | 433ms | 14ms | 3.34
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| UserStore.GetMany | p99 | 244ms | 4.325s | 4.081s | 1669.12
| ProductNoticesStore.ClearOldNotices | p99 | 5ms | 50ms | 45ms | 908.81
| RoleStore.ChannelHigherScopedPermissions | p99 | 228ms | 988ms | 760ms | 332.61
| UserStore.GetByUsername | p99 | 547ms | 1.379s | 832ms | 151.96
| UserStore.GetProfilesInChannel | p99 | 99ms | 246ms | 147ms | 148.48
| PreferenceStore.DeleteCategoryAndName | p99 | 98ms | 238ms | 140ms | 143.15
| PostStore.GetPostReminderMetadata | p99 | 720ms | 1.69s | 970ms | 134.72
| JobStore.GetNewestJobByStatusesAndType | p99 | 405ms | 917ms | 512ms | 126.42
| CommandWebhookStore.Cleanup | p99 | 50ms | 98ms | 48ms | 96.97
| TokenStore.Cleanup | p99 | 50ms | 98ms | 48ms | 96.97
| PostStore.SetPostReminder | p99 | 241ms | 466ms | 225ms | 93.24
| PostStore.GetPostReminders | p99 | 229ms | 425ms | 196ms | 85.59
| StatusStore.SaveOrUpdate | p99 | 1.217s | 2.255s | 1.038s | 85.28
| UserAccessTokenStore.GetByToken | p99 | 450ms | 815ms | 365ms | 81.11
| PostAcknowledgementStore.GetForPost | p99 | 487ms | 796ms | 309ms | 63.38
| StatusStore.GetByIds | p99 | 525ms | 797ms | 272ms | 51.81
| UserStore.IsEmpty | p99 | 288ms | 392ms | 104ms | 36.15
| JobStore.UpdateStatusOptimistically | p99 | 141ms | 190ms | 49ms | 34.87
| JobStore.UpdateOptimistically | p99 | 97ms | 130ms | 33ms | 34.13
| ChannelStore.GetMemberCount | p99 | 1.358s | 1.82s | 462ms | 34.02
| JobStore.GetCountByStatusAndType | p99 | 437ms | 585ms | 148ms | 33.89
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 473ms | 632ms | 159ms | 33.58
| PreferenceStore.Save | p99 | 304ms | 396ms | 92ms | 30.23
| PostAcknowledgementStore.GetForPosts | p99 | 1.047s | 1.352s | 305ms | 29.12
| UserStore.GetUnreadCount | p99 | 583ms | 748ms | 165ms | 28.29
| UserStore.Search | p99 | 1.183s | 1.484s | 301ms | 25.45
| PostStore.GetPostsAfter | p99 | 626ms | 777ms | 151ms | 24.12
| TeamStore.SaveMember | p99 | 601ms | 743ms | 142ms | 23.62
| ChannelStore.AutocompleteInTeamForSearch | p99 | 2.466s | 3.026s | 560ms | 22.71
| PostPriorityStore.GetForPosts | p99 | 1.15s | 1.407s | 257ms | 22.34
| ChannelStore.GetPinnedPostCount | p99 | 570ms | 683ms | 113ms | 19.82
| ChannelStore.SearchGroupChannels | p99 | 744ms | 871ms | 127ms | 17.07
| ChannelStore.GetPublicChannelsForTeam | p99 | 693ms | 810ms | 117ms | 16.88
| GroupStore.GetGroups | p99 | 576ms | 670ms | 94ms | 16.31
| UserStore.GetProfilesByUsernames | p99 | 498ms | 579ms | 81ms | 16.27
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 557ms | 646ms | 89ms | 15.99
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 157ms | 182ms | 25ms | 15.96
| ChannelStore.GetMember | p99 | 271ms | 312ms | 41ms | 15.11
| PreferenceStore.GetAll | p99 | 492ms | 566ms | 74ms | 15.04
| ChannelStore.Autocomplete | p99 | 6.765s | 7.723s | 958ms | 14.16
| UserStore.GetProfileByIds | p99 | 492ms | 558ms | 66ms | 13.42
| ChannelStore.GetAllChannelMembersForUser | p99 | 247ms | 280ms | 33ms | 13.36
| TeamStore.Get | p99 | 585ms | 658ms | 73ms | 12.47
| ChannelStore.GetGuestCount | p99 | 655ms | 736ms | 81ms | 12.36
| PostStore.Get | p99 | 974ms | 1.091s | 117ms | 12.01
| ReactionStore.GetForPost | p99 | 726ms | 813ms | 87ms | 11.98
| ThreadStore.GetTotalThreads | p99 | 492ms | 550ms | 58ms | 11.80
| ThreadStore.MarkAsRead | p99 | 163ms | 182ms | 19ms | 11.62
| PostStore.GetSingle | p99 | 625ms | 695ms | 70ms | 11.20
| ChannelStore.GetMembersForUser | p99 | 661ms | 735ms | 74ms | 11.19
| PreferenceStore.Get | p99 | 644ms | 712ms | 68ms | 10.56
| FileInfoStore.GetForPost | p99 | 758ms | 838ms | 80ms | 10.55
| GroupStore.GetByName | p99 | 421ms | 465ms | 44ms | 10.46
| PostStore.GetPostsByThread | p99 | 629ms | 690ms | 61ms | 9.70
| ChannelStore.GetByName | p99 | 433ms | 473ms | 40ms | 9.23
| ChannelStore.SaveMember | p99 | 1.945s | 2.118s | 173ms | 8.89
| LinkMetadataStore.Get | p99 | 644ms | 701ms | 57ms | 8.86
| PostStore.GetPostsBefore | p99 | 657ms | 714ms | 57ms | 8.68
| UserStore.UpdateFailedPasswordAttempts | p99 | 176ms | 191ms | 15ms | 8.50
| PostStore.GetPosts | p99 | 424ms | 460ms | 36ms | 8.50
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 412ms | 447ms | 35ms | 8.50
| ThreadStore.GetThreadUnreadReplyCount | p99 | 720ms | 778ms | 58ms | 8.05
| JobStore.Save | p99 | 194ms | 209ms | 15ms | 7.74
| TeamStore.GetByName | p99 | 584ms | 629ms | 45ms | 7.70
| ThreadStore.GetTotalUnreadMentions | p99 | 491ms | 528ms | 37ms | 7.53
| PostStore.GetEtag | p99 | 713ms | 765ms | 52ms | 7.30
| UserStore.GetAllProfiles | p99 | 473ms | 507ms | 34ms | 7.18
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 488ms | 521ms | 33ms | 6.76
| PostStore.GetPostIdAfterTime | p99 | 149ms | 159ms | 10ms | 6.69
| WebhookStore.GetOutgoingByTeam | p99 | 691ms | 737ms | 46ms | 6.66
| ThreadStore.GetMembershipForUser | p99 | 627ms | 668ms | 41ms | 6.54
| ThreadStore.MaintainMembership | p99 | 329ms | 350ms | 21ms | 6.38
| UserStore.UpdateUpdateAt | p99 | 111ms | 118ms | 7ms | 6.33
| PostStore.GetPostsSince | p99 | 823ms | 873ms | 50ms | 6.07
| ThreadStore.GetThreadsForUser | p99 | 775ms | 822ms | 47ms | 6.06
| AuditStore.Save | p99 | 172ms | 182ms | 10ms | 5.83
| ChannelStore.GetChannels | p99 | 729ms | 769ms | 40ms | 5.48
| UserStore.GetForLogin | p99 | 457ms | 482ms | 25ms | 5.47
| SystemStore.GetByName | p99 | 147ms | 155ms | 8ms | 5.46
| ChannelStore.GetFileCount | p99 | 440ms | 464ms | 24ms | 5.45
| TeamStore.GetTeamsByUserId | p99 | 473ms | 496ms | 23ms | 4.86
| UserTermsOfServiceStore.GetByUser | p99 | 473ms | 496ms | 23ms | 4.86
| ThreadStore.GetThreadFollowers | p99 | 677ms | 707ms | 30ms | 4.43
| ThreadStore.Get | p99 | 638ms | 665ms | 27ms | 4.24
| TeamStore.GetAllPage | p99 | 475ms | 495ms | 20ms | 4.21
| PostStore.SearchPostsForUser | p99 | 2.495s | 2.6s | 105ms | 4.21
| UserStore.Get | p99 | 398ms | 414ms | 16ms | 4.02
| ChannelStore.CreateInitialSidebarCategories | p99 | 825ms | 857ms | 32ms | 3.88
| ThreadStore.GetThreadForUser | p99 | 898ms | 932ms | 34ms | 3.79
| ThreadStore.MarkAllAsReadByChannels | p99 | 216ms | 224ms | 8ms | 3.71
| SessionStore.UpdateLastActivityAt | p99 | 189ms | 196ms | 7ms | 3.70
| StatusStore.Get | p99 | 407ms | 422ms | 15ms | 3.69
| TeamStore.GetMember | p99 | 95ms | 98ms | 3ms | 3.15
| FileInfoStore.Get | p99 | 494ms | 509ms | 15ms | 3.04
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 485ms | 499ms | 14ms | 2.89
| UserStore.AutocompleteUsersInChannel | p99 | 2.294s | 2.357s | 63ms | 2.75
| ChannelStore.Get | p99 | 853ms | 876ms | 23ms | 2.70
| ThreadStore.UpdateMembership | p99 | 199ms | 204ms | 5ms | 2.52
| PostStore.GetPostIdBeforeTime | p99 | 200ms | 205ms | 5ms | 2.50
| ChannelStore.IncrementMentionCount | p99 | 200ms | 205ms | 5ms | 2.49
| ChannelStore.CreateSidebarCategory | p99 | 483ms | 495ms | 12ms | 2.49
| ThreadStore.GetTeamsUnreadForUser | p99 | 877ms | 898ms | 21ms | 2.39
| ProductNoticesStore.View | p99 | 956ms | 978ms | 22ms | 2.30
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 450ms | 460ms | 10ms | 2.22
| UserStore.GetAllProfilesInChannel | p99 | 4.75s | 4.85s | 100ms | 2.11
| PostPersistentNotificationStore.GetSingle | p99 | 641ms | 654ms | 13ms | 2.03
| FileInfoStore.Save | p99 | 213ms | 217ms | 4ms | 1.87
| FileInfoStore.SetContent | p99 | 242ms | 246ms | 4ms | 1.65
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 1.149s | 1.166s | 17ms | 1.48
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 135ms | 137ms | 2ms | 1.48
| SessionStore.Save | p99 | 492ms | 499ms | 7ms | 1.42
| StatusStore.UpdateLastActivityAt | p99 | 219ms | 222ms | 3ms | 1.37
| PluginStore.SetWithOptions | p99 | 228ms | 231ms | 3ms | 1.32
| ChannelStore.GetMembers | p99 | 2.232s | 2.261s | 29ms | 1.30
| SessionStore.Get | p99 | 239ms | 242ms | 3ms | 1.26
| ChannelStore.GetMemberForPost | p99 | 483ms | 489ms | 6ms | 1.24
| PostStore.Save | p99 | 486ms | 492ms | 6ms | 1.23
| ReactionStore.Save | p99 | 454ms | 459ms | 5ms | 1.10
| PostStore.AnalyticsPostCount | p99 | 9.9s | 10s | 100ms | 1.01
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| TeamStore.GetMany | avg | 52ms | 0s | -52ms | -100.68
| PostStore.GetPostsByIds | avg | 63ms | 0s | -63ms | -100.14
| PostPersistentNotificationStore.UpdateLastActivity | avg | 29ms | 0s | -29ms | -99.48
| ChannelStore.GetChannelsByIds | avg | 70ms | 0s | -70ms | -99.33
| PostPersistentNotificationStore.DeleteExpired | avg | 19ms | 6ms | -13ms | -69.13
| ThreadStore.MarkAllAsReadByTeam | avg | 25ms | 10ms | -15ms | -61.01
| LinkMetadataStore.Save | avg | 18ms | 8ms | -10ms | -54.87
| PostPersistentNotificationStore.Get | avg | 24ms | 12ms | -12ms | -49.14
| JobStore.UpdateStatus | avg | 17ms | 9ms | -8ms | -46.13
| SessionStore.GetSessionsExpired | avg | 80ms | 44ms | -36ms | -45.22
| JobStore.UpdateOptimistically | avg | 18ms | 12ms | -6ms | -32.62
| JobStore.UpdateStatusOptimistically | avg | 24ms | 17ms | -7ms | -29.66
| ChannelStore.GetSidebarCategory | avg | 138ms | 99ms | -39ms | -28.31
| SessionStore.Remove | avg | 24ms | 18ms | -6ms | -25.43
| BotStore.Get | avg | 78ms | 61ms | -17ms | -21.79
| StatusStore.UpdateExpiredDNDStatuses | avg | 50ms | 40ms | -10ms | -19.84
| ChannelStore.UpdateSidebarCategories | avg | 384ms | 323ms | -61ms | -15.88
| PostStore.Update | avg | 82ms | 69ms | -13ms | -15.83
| ChannelStore.CreateDirectChannel | avg | 300ms | 258ms | -42ms | -14.00
| PostStore.Delete | avg | 177ms | 161ms | -16ms | -9.02
| ClusterDiscoveryStore.SetLastPingAt | avg | 23ms | 21ms | -2ms | -8.70
| PostStore.GetPostReminders | avg | 35ms | 32ms | -3ms | -8.56
| PostStore.GetPostReminderMetadata | avg | 70ms | 64ms | -6ms | -8.55
| ChannelStore.Save | avg | 140ms | 133ms | -7ms | -4.99
| UserStore.Update | avg | 47ms | 45ms | -2ms | -4.25
| ChannelStore.GetChannelUnread | avg | 98ms | 94ms | -4ms | -4.07
| PostStore.SearchPostsForUser | avg | 197ms | 189ms | -8ms | -4.05
| PostPriorityStore.GetForPost | avg | 63ms | 61ms | -2ms | -3.18
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PostPersistentNotificationStore.UpdateLastActivity | p99 | 98ms | 0s | -98ms | -99.92
| ChannelStore.GetChannelsByIds | p99 | 246ms | 0s | -246ms | -99.90
| TeamStore.GetMany | p99 | 99ms | 0s | -99ms | -99.83
| PostStore.GetPostsByIds | p99 | 99ms | 0s | -99ms | -99.66
| LinkMetadataStore.Save | p99 | 212ms | 76ms | -136ms | -64.23
| SessionStore.Remove | p99 | 219ms | 96ms | -123ms | -56.29
| ThreadStore.MarkAllAsReadByTeam | p99 | 49ms | 25ms | -24ms | -48.73
| PostStore.Delete | p99 | 945ms | 490ms | -455ms | -48.15
| BotStore.Get | p99 | 860ms | 463ms | -397ms | -46.16
| PluginStore.List | p99 | 720ms | 470ms | -250ms | -34.72
| JobStore.UpdateStatus | p99 | 91ms | 60ms | -31ms | -34.11
| PostPriorityStore.GetForPost | p99 | 917ms | 637ms | -280ms | -30.52
| ChannelStore.GetSidebarCategory | p99 | 985ms | 750ms | -235ms | -23.86
| PostPersistentNotificationStore.DeleteExpired | p99 | 97ms | 76ms | -21ms | -21.70
| PostPersistentNotificationStore.Get | p99 | 224ms | 178ms | -46ms | -20.49
| ChannelStore.Save | p99 | 950ms | 765ms | -185ms | -19.47
| ChannelStore.CreateDirectChannel | p99 | 2.254s | 1.947s | -307ms | -13.62
| JobStore.GetAllByStatus | p99 | 950ms | 824ms | -126ms | -13.26
| JobStore.Get | p99 | 1.405s | 1.3s | -105ms | -7.47
| ChannelStore.GetChannelsByUser | p99 | 785ms | 737ms | -48ms | -6.12
| SessionStore.GetSessionsExpired | p99 | 246ms | 232ms | -14ms | -5.69
| ChannelStore.GetChannelUnread | p99 | 836ms | 791ms | -45ms | -5.38
| ChannelStore.UpdateSidebarCategories | p99 | 2.235s | 2.125s | -110ms | -4.92
| ClusterDiscoveryStore.SetLastPingAt | p99 | 212ms | 205ms | -7ms | -3.31
| FileInfoStore.AttachToPost | p99 | 242ms | 235ms | -7ms | -2.90
| UserStore.Count | p99 | 985ms | 972ms | -13ms | -1.32
| TeamStore.GetTeamsForUser | p99 | 486ms | 480ms | -6ms | -1.24
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| patchPost | avg | 1.474s | 6.638s | 5.164s | 350.40
| getChannelMembers | avg | 46ms | 147ms | 101ms | 221.53
| createCategoryForTeamForUser | avg | 183ms | 295ms | 112ms | 61.11
| followThreadByUser | avg | 180ms | 257ms | 77ms | 42.69
| getPublicChannelsForTeam | avg | 89ms | 111ms | 22ms | 24.82
| deletePost | avg | 359ms | 447ms | 88ms | 24.48
| getChannelStats | avg | 104ms | 128ms | 24ms | 23.03
| getTeamsForUser | avg | 53ms | 63ms | 10ms | 18.83
| searchGroupChannels | avg | 84ms | 99ms | 15ms | 17.85
| addTeamMember | avg | 2.882s | 3.374s | 492ms | 17.07
| createChannel | avg | 148ms | 171ms | 23ms | 15.57
| getPreferences | avg | 59ms | 68ms | 9ms | 15.26
| getAllTeams | avg | 53ms | 61ms | 8ms | 15.17
| getUser | avg | 71ms | 81ms | 10ms | 14.13
| getPostsForChannelAroundLastUnread | avg | 243ms | 276ms | 33ms | 13.59
| getUsers | avg | 64ms | 72ms | 8ms | 12.40
| getTeamsUnreadForUser | avg | 91ms | 102ms | 11ms | 12.10
| searchAllChannels | avg | 365ms | 408ms | 43ms | 11.79
| getChannelMembersForTeamForUser | avg | 70ms | 78ms | 8ms | 11.39
| getCategoriesForTeamForUser | avg | 125ms | 139ms | 14ms | 11.23
| createUser | avg | 227ms | 252ms | 25ms | 10.99
| getPostsForChannel | avg | 859ms | 946ms | 87ms | 10.13
| getUsersByNames | avg | 62ms | 68ms | 6ms | 9.75
| saveReaction | avg | 288ms | 316ms | 28ms | 9.73
| searchUsers | avg | 195ms | 214ms | 19ms | 9.72
| updatePreferences | avg | 84ms | 92ms | 8ms | 9.54
| updateReadStateThreadByUser | avg | 588ms | 644ms | 56ms | 9.52
| getThreadsForUser | avg | 87ms | 95ms | 8ms | 9.25
| getChannelsForTeamForUser | avg | 78ms | 85ms | 7ms | 9.02
| autocompleteUsers | avg | 465ms | 505ms | 40ms | 8.60
| addChannelMember | avg | 1.456s | 1.58s | 124ms | 8.52
| viewChannel | avg | 192ms | 208ms | 16ms | 8.32
| getPostThread | avg | 416ms | 450ms | 34ms | 8.17
| autocompleteChannelsForTeamForSearch | avg | 443ms | 479ms | 36ms | 8.12
| login | avg | 301ms | 321ms | 20ms | 6.64
| createPost | avg | 3.8s | 4.042s | 242ms | 6.37
| getFileThumbnail | avg | 163ms | 172ms | 9ms | 5.51
| getTeamMembersForUser | avg | 55ms | 58ms | 3ms | 5.44
| getChannelMember | avg | 79ms | 83ms | 4ms | 5.07
| getFilePreview | avg | 174ms | 180ms | 6ms | 3.46
| getChannelsForUser | avg | 87ms | 90ms | 3ms | 3.45
| searchPostsInTeam | avg | 383ms | 390ms | 7ms | 1.83
| createGroupChannel | avg | 1.81s | 1.835s | 25ms | 1.38
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| followThreadByUser | p99 | 493ms | 2.02s | 1.527s | 309.79
| patchPost | p99 | 4.062s | 10s | 5.938s | 146.17
| getChannelMembers | p99 | 239ms | 492ms | 253ms | 105.64
| deletePost | p99 | 2.335s | 4.6s | 2.265s | 97.00
| addChannelMember | p99 | 4.997s | 7.764s | 2.767s | 55.38
| getUser | p99 | 605ms | 761ms | 156ms | 25.78
| createUser | p99 | 1.443s | 1.814s | 371ms | 25.71
| getChannelStats | p99 | 1.452s | 1.825s | 373ms | 25.68
| searchUsers | p99 | 1.234s | 1.531s | 297ms | 24.06
| autocompleteChannelsForTeamForSearch | p99 | 2.466s | 3.026s | 560ms | 22.71
| getUsers | p99 | 610ms | 747ms | 137ms | 22.47
| getPostThread | p99 | 2.491s | 3.023s | 532ms | 21.36
| getUsersByNames | p99 | 515ms | 606ms | 91ms | 17.66
| searchGroupChannels | p99 | 744ms | 871ms | 127ms | 17.07
| getPublicChannelsForTeam | p99 | 693ms | 810ms | 117ms | 16.88
| getPreferences | p99 | 493ms | 574ms | 81ms | 16.42
| getChannelMembersForTeamForUser | p99 | 661ms | 739ms | 78ms | 11.80
| searchAllChannels | p99 | 6.931s | 7.723s | 792ms | 11.43
| updateReadStateThreadByUser | p99 | 3.669s | 4.064s | 395ms | 10.77
| viewChannel | p99 | 1.563s | 1.728s | 165ms | 10.55
| getUsersByIds | p99 | 198ms | 211ms | 13ms | 6.57
| getClientConfig | p99 | 352ms | 375ms | 23ms | 6.54
| getChannelMember | p99 | 680ms | 720ms | 40ms | 5.88
| getChannelsForTeamForUser | p99 | 727ms | 767ms | 40ms | 5.50
| getTeamsForUser | p99 | 474ms | 497ms | 23ms | 4.85
| getThreadsForUser | p99 | 850ms | 891ms | 41ms | 4.83
| saveReaction | p99 | 2.143s | 2.238s | 95ms | 4.43
| logout | p99 | 1.87s | 1.945s | 75ms | 4.01
| getPostsForChannel | p99 | 9.116s | 9.43s | 314ms | 3.44
| getAllTeams | p99 | 482ms | 498ms | 16ms | 3.32
| createDirectChannel | p99 | 4.493s | 4.639s | 146ms | 3.25
| getCategoriesForTeamForUser | p99 | 1.149s | 1.18s | 31ms | 2.70
| autocompleteUsers | p99 | 2.268s | 2.327s | 59ms | 2.60
| getTeamsUnreadForUser | p99 | 943ms | 966ms | 23ms | 2.44
| getPostsForChannelAroundLastUnread | p99 | 2.322s | 2.366s | 44ms | 1.89
| createCategoryForTeamForUser | p99 | 965ms | 980ms | 15ms | 1.55
| updatePreferences | p99 | 470ms | 476ms | 6ms | 1.28
| getFileThumbnail | p99 | 979ms | 991ms | 12ms | 1.23
| removeUserCustomStatus | p99 | 2.357s | 2.383s | 26ms | 1.10
| login | p99 | 2.371s | 2.395s | 24ms | 1.01
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateReadStateAllThreadsByUser | avg | 25ms | 10ms | -15ms | -60.70
| setPostReminder | avg | 364ms | 265ms | -99ms | -27.19
| updateCategoriesForTeamForUser | avg | 738ms | 585ms | -153ms | -20.72
| getTeamMember | avg | 31ms | 27ms | -4ms | -12.99
| unfollowThreadByUser | avg | 268ms | 235ms | -33ms | -12.31
| getProfileImage | avg | 108ms | 100ms | -8ms | -7.39
| logout | avg | 346ms | 322ms | -24ms | -6.93
| updateUserCustomStatus | avg | 646ms | 612ms | -34ms | -5.26
| removeUserCustomStatus | avg | 527ms | 500ms | -27ms | -5.13
| getChannelUnread | avg | 108ms | 103ms | -5ms | -4.62
| uploadFileStream | avg | 598ms | 578ms | -20ms | -3.35
| getChannel | avg | 134ms | 130ms | -4ms | -2.98
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| setPostReminder | p99 | 4.275s | 2.095s | -2.18s | -50.99
| updateReadStateAllThreadsByUser | p99 | 49ms | 25ms | -24ms | -48.73
| getChannel | p99 | 1.364s | 950ms | -414ms | -30.36
| createGroupChannel | p99 | 8.25s | 6.475s | -1.775s | -21.52
| unfollowThreadByUser | p99 | 1.555s | 1.248s | -307ms | -19.74
| getChannelsForUser | p99 | 785ms | 737ms | -48ms | -6.12
| getChannelUnread | p99 | 902ms | 859ms | -43ms | -4.77
| getTeamMember | p99 | 242ms | 236ms | -6ms | -2.48
| searchPostsInTeam | p99 | 4.729s | 4.624s | -105ms | -2.22
| getUserStatusesByIds | p99 | 90ms | 88ms | -2ms | -2.22
| updateCategoriesForTeamForUser | p99 | 2.447s | 2.393s | -54ms | -2.21
| updateUserCustomStatus | p99 | 2.463s | 2.415s | -48ms | -1.95
| uploadFileStream | p99 | 2.399s | 2.375s | -24ms | -1.00
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 172ms| 182ms | 10ms | 5.827
| BotStore.Get |  Avg| 78ms| 61ms | -17ms | -21.787
| |  P99| 860ms| 463ms | -397ms | -46.163
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 13ms| 12ms | -1ms | -7.854
| |  P99| 135ms| 137ms | 2ms | 1.479
| ChannelStore.Autocomplete |  Avg| 361ms| 405ms | 44ms | 12.176
| |  P99| 6.765s| 7.723s | 958ms | 14.161
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 443ms| 478ms | 35ms | 7.899
| |  P99| 2.466s| 3.026s | 560ms | 22.708
| ChannelStore.CreateDirectChannel |  Avg| 300ms| 258ms | -42ms | -14.002
| |  P99| 2.254s| 1.947s | -307ms | -13.618
| ChannelStore.CreateInitialSidebarCategories |  Avg| 91ms| 99ms | 8ms | 8.798
| |  P99| 825ms| 857ms | 32ms | 3.877
| ChannelStore.CreateSidebarCategory |  Avg| 143ms| 264ms | 121ms | 84.577
| |  P99| 483ms| 495ms | 12ms | 2.487
| ChannelStore.Get |  Avg| 94ms| 101ms | 7ms | 7.457
| |  P99| 853ms| 876ms | 23ms | 2.696
| ChannelStore.GetAllChannelMembersForUser |  Avg| 13ms| 14ms | 1ms | 7.749
| |  P99| 247ms| 280ms | 33ms | 13.355
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 68ms| 68ms | 0s | 0.000
| |  P99| 450ms| 460ms | 10ms | 2.221
| ChannelStore.GetByName |  Avg| 39ms| 46ms | 7ms | 18.009
| |  P99| 433ms| 473ms | 40ms | 9.232
| ChannelStore.GetChannelUnread |  Avg| 98ms| 94ms | -4ms | -4.068
| |  P99| 836ms| 791ms | -45ms | -5.380
| ChannelStore.GetChannels |  Avg| 78ms| 85ms | 7ms | 8.951
| |  P99| 729ms| 769ms | 40ms | 5.484
| ChannelStore.GetChannelsByIds |  Avg| 70ms| 0s | -70ms | -99.328
| |  P99| 246ms| 0s | -246ms | -99.899
| ChannelStore.GetChannelsByUser |  Avg| 87ms| 90ms | 3ms | 3.463
| |  P99| 785ms| 737ms | -48ms | -6.117
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 60ms| 67ms | 7ms | 11.707
| |  P99| 557ms| 646ms | 89ms | 15.991
| ChannelStore.GetFileCount |  Avg| 49ms| 55ms | 6ms | 12.351
| |  P99| 440ms| 464ms | 24ms | 5.454
| ChannelStore.GetGuestCount |  Avg| 66ms| 80ms | 14ms | 21.197
| |  P99| 655ms| 736ms | 81ms | 12.359
| ChannelStore.GetMember |  Avg| 22ms| 24ms | 2ms | 9.071
| |  P99| 271ms| 312ms | 41ms | 15.106
| ChannelStore.GetMemberCount |  Avg| 354ms| 434ms | 80ms | 22.615
| |  P99| 1.358s| 1.82s | 462ms | 34.023
| ChannelStore.GetMemberForPost |  Avg| 52ms| 55ms | 3ms | 5.767
| |  P99| 483ms| 489ms | 6ms | 1.243
| ChannelStore.GetMembers |  Avg| 419ms| 433ms | 14ms | 3.339
| |  P99| 2.232s| 2.261s | 29ms | 1.299
| ChannelStore.GetMembersForUser |  Avg| 70ms| 77ms | 7ms | 9.976
| |  P99| 661ms| 735ms | 74ms | 11.188
| ChannelStore.GetPinnedPostCount |  Avg| 63ms| 73ms | 10ms | 15.805
| |  P99| 570ms| 683ms | 113ms | 19.816
| ChannelStore.GetPublicChannelsForTeam |  Avg| 87ms| 109ms | 22ms | 25.344
| |  P99| 693ms| 810ms | 117ms | 16.883
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 124ms| 138ms | 14ms | 11.278
| |  P99| 1.149s| 1.166s | 17ms | 1.480
| ChannelStore.GetSidebarCategory |  Avg| 138ms| 99ms | -39ms | -28.309
| |  P99| 985ms| 750ms | -235ms | -23.858
| ChannelStore.GetTeamChannels |  Avg| 138ms| 171ms | 33ms | 23.840
| |  P99| 488ms| 489ms | 1ms | 0.205
| ChannelStore.IncrementMentionCount |  Avg| 19ms| 19ms | 0s | 0.000
| |  P99| 200ms| 205ms | 5ms | 2.494
| ChannelStore.InvalidateAllChannelMembersForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateChannelByName |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 140ms| 133ms | -7ms | -4.992
| |  P99| 950ms| 765ms | -185ms | -19.474
| ChannelStore.SaveMember |  Avg| 195ms| 238ms | 43ms | 22.055
| |  P99| 1.945s| 2.118s | 173ms | 8.894
| ChannelStore.SearchGroupChannels |  Avg| 84ms| 99ms | 15ms | 17.897
| |  P99| 744ms| 871ms | 127ms | 17.067
| ChannelStore.UpdateLastViewedAt |  Avg| 38ms| 39ms | 1ms | 2.612
| |  P99| 244ms| 246ms | 2ms | 0.821
| ChannelStore.UpdateSidebarCategories |  Avg| 384ms| 323ms | -61ms | -15.877
| |  P99| 2.235s| 2.125s | -110ms | -4.922
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 18ms| 20ms | 2ms | 11.100
| |  P99| 157ms| 182ms | 25ms | 15.963
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 23ms| 21ms | -2ms | -8.705
| |  P99| 212ms| 205ms | -7ms | -3.309
| CommandWebhookStore.Cleanup |  Avg| 20ms| 30ms | 10ms | 50.202
| |  P99| 50ms| 98ms | 48ms | 96.970
| FileInfoStore.AttachToPost |  Avg| 33ms| 32ms | -1ms | -3.022
| |  P99| 242ms| 235ms | -7ms | -2.896
| FileInfoStore.Get |  Avg| 57ms| 60ms | 3ms | 5.254
| |  P99| 494ms| 509ms | 15ms | 3.039
| FileInfoStore.GetForPost |  Avg| 77ms| 87ms | 10ms | 13.040
| |  P99| 758ms| 838ms | 80ms | 10.552
| FileInfoStore.Save |  Avg| 25ms| 25ms | 0s | 0.000
| |  P99| 213ms| 217ms | 4ms | 1.875
| FileInfoStore.SetContent |  Avg| 44ms| 43ms | -1ms | -2.294
| |  P99| 242ms| 246ms | 4ms | 1.653
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 38ms| 48ms | 10ms | 26.190
| |  P99| 412ms| 447ms | 35ms | 8.495
| GroupStore.GetByName |  Avg| 35ms| 45ms | 10ms | 28.244
| |  P99| 421ms| 465ms | 44ms | 10.456
| GroupStore.GetGroups |  Avg| 60ms| 68ms | 8ms | 13.232
| |  P99| 576ms| 670ms | 94ms | 16.306
| JobStore.Get |  Avg| 76ms| 79ms | 3ms | 3.940
| |  P99| 1.405s| 1.3s | -105ms | -7.474
| JobStore.GetAllByStatus |  Avg| 75ms| 78ms | 3ms | 3.980
| |  P99| 950ms| 824ms | -126ms | -13.263
| JobStore.GetCountByStatusAndType |  Avg| 58ms| 66ms | 8ms | 13.685
| |  P99| 437ms| 585ms | 148ms | 33.893
| JobStore.GetNewestJobByStatusesAndType |  Avg| 51ms| 81ms | 30ms | 58.774
| |  P99| 405ms| 917ms | 512ms | 126.420
| JobStore.Save |  Avg| 18ms| 21ms | 3ms | 16.331
| |  P99| 194ms| 209ms | 15ms | 7.742
| JobStore.UpdateOptimistically |  Avg| 18ms| 12ms | -6ms | -32.623
| |  P99| 97ms| 130ms | 33ms | 34.133
| JobStore.UpdateStatus |  Avg| 17ms| 9ms | -8ms | -46.128
| |  P99| 91ms| 60ms | -31ms | -34.113
| JobStore.UpdateStatusOptimistically |  Avg| 24ms| 17ms | -7ms | -29.660
| |  P99| 141ms| 190ms | 49ms | 34.871
| LinkMetadataStore.Get |  Avg| 65ms| 71ms | 6ms | 9.192
| |  P99| 644ms| 701ms | 57ms | 8.857
| LinkMetadataStore.Save |  Avg| 18ms| 8ms | -10ms | -54.871
| |  P99| 212ms| 76ms | -136ms | -64.227
| PluginStore.Delete |  Avg| 10ms| 9ms | -1ms | -10.267
| |  P99| 100ms| 100ms | 0s | 0.000
| PluginStore.List |  Avg| 74ms| 73ms | -1ms | -1.343
| |  P99| 720ms| 470ms | -250ms | -34.722
| PluginStore.SetWithOptions |  Avg| 22ms| 21ms | -1ms | -4.548
| |  P99| 228ms| 231ms | 3ms | 1.317
| PostAcknowledgementStore.GetForPost |  Avg| 48ms| 62ms | 14ms | 29.076
| |  P99| 487ms| 796ms | 309ms | 63.385
| PostAcknowledgementStore.GetForPosts |  Avg| 101ms| 113ms | 12ms | 11.889
| |  P99| 1.047s| 1.352s | 305ms | 29.124
| PostPersistentNotificationStore.DeleteExpired |  Avg| 19ms| 6ms | -13ms | -69.134
| |  P99| 97ms| 76ms | -21ms | -21.697
| PostPersistentNotificationStore.Get |  Avg| 24ms| 12ms | -12ms | -49.140
| |  P99| 224ms| 178ms | -46ms | -20.490
| PostPersistentNotificationStore.GetSingle |  Avg| 66ms| 72ms | 6ms | 9.146
| |  P99| 641ms| 654ms | 13ms | 2.029
| PostPersistentNotificationStore.UpdateLastActivity |  Avg| 29ms| 0s | -29ms | -99.479
| |  P99| 98ms| 0s | -98ms | -99.917
| PostPriorityStore.GetForPost |  Avg| 63ms| 61ms | -2ms | -3.182
| |  P99| 917ms| 637ms | -280ms | -30.518
| PostPriorityStore.GetForPosts |  Avg| 106ms| 119ms | 13ms | 12.243
| |  P99| 1.15s| 1.407s | 257ms | 22.343
| PostStore.AnalyticsPostCount |  Avg| 5.302s| 10.773s | 5.471s | 103.184
| |  P99| 9.9s| 10s | 100ms | 1.010
| PostStore.Delete |  Avg| 177ms| 161ms | -16ms | -9.017
| |  P99| 945ms| 490ms | -455ms | -48.148
| PostStore.Get |  Avg| 133ms| 144ms | 11ms | 8.277
| |  P99| 974ms| 1.091s | 117ms | 12.015
| PostStore.GetEtag |  Avg| 73ms| 82ms | 9ms | 12.268
| |  P99| 713ms| 765ms | 52ms | 7.296
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 149ms| 159ms | 10ms | 6.689
| PostStore.GetPostIdBeforeTime |  Avg| 20ms| 20ms | 0s | 0.000
| |  P99| 200ms| 205ms | 5ms | 2.496
| PostStore.GetPostReminderMetadata |  Avg| 70ms| 64ms | -6ms | -8.550
| |  P99| 720ms| 1.69s | 970ms | 134.721
| PostStore.GetPostReminders |  Avg| 35ms| 32ms | -3ms | -8.562
| |  P99| 229ms| 425ms | 196ms | 85.590
| PostStore.GetPosts |  Avg| 42ms| 50ms | 8ms | 19.132
| |  P99| 424ms| 460ms | 36ms | 8.496
| PostStore.GetPostsAfter |  Avg| 73ms| 74ms | 1ms | 1.376
| |  P99| 626ms| 777ms | 151ms | 24.121
| PostStore.GetPostsBefore |  Avg| 71ms| 79ms | 8ms | 11.196
| |  P99| 657ms| 714ms | 57ms | 8.676
| PostStore.GetPostsByIds |  Avg| 63ms| 0s | -63ms | -100.145
| |  P99| 99ms| 0s | -99ms | -99.664
| PostStore.GetPostsByThread |  Avg| 66ms| 72ms | 6ms | 9.110
| |  P99| 629ms| 690ms | 61ms | 9.698
| PostStore.GetPostsSince |  Avg| 113ms| 126ms | 13ms | 11.468
| |  P99| 823ms| 873ms | 50ms | 6.074
| PostStore.GetSingle |  Avg| 63ms| 68ms | 5ms | 7.993
| |  P99| 625ms| 695ms | 70ms | 11.201
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 66ms| 66ms | 0s | 0.000
| |  P99| 486ms| 492ms | 6ms | 1.234
| PostStore.SearchPostsForUser |  Avg| 197ms| 189ms | -8ms | -4.054
| |  P99| 2.495s| 2.6s | 105ms | 4.208
| PostStore.SetPostReminder |  Avg| 47ms| 77ms | 30ms | 64.100
| |  P99| 241ms| 466ms | 225ms | 93.245
| PostStore.Update |  Avg| 82ms| 69ms | -13ms | -15.825
| |  P99| 445ms| 445ms | 0s | 0.000
| PreferenceStore.DeleteCategoryAndName |  Avg| 29ms| 42ms | 13ms | 44.674
| |  P99| 98ms| 238ms | 140ms | 143.149
| PreferenceStore.Get |  Avg| 67ms| 73ms | 6ms | 8.955
| |  P99| 644ms| 712ms | 68ms | 10.561
| PreferenceStore.GetAll |  Avg| 58ms| 67ms | 9ms | 15.468
| |  P99| 492ms| 566ms | 74ms | 15.040
| PreferenceStore.Save |  Avg| 36ms| 43ms | 7ms | 19.556
| |  P99| 304ms| 396ms | 92ms | 30.234
| ProductNoticesStore.ClearOldNotices |  Avg| 2ms| 18ms | 16ms | 950.318
| |  P99| 5ms| 50ms | 45ms | 908.813
| ProductNoticesStore.View |  Avg| 121ms| 120ms | -1ms | -0.829
| |  P99| 956ms| 978ms | 22ms | 2.301
| ReactionStore.GetForPost |  Avg| 79ms| 86ms | 7ms | 8.872
| |  P99| 726ms| 813ms | 87ms | 11.977
| ReactionStore.Save |  Avg| 71ms| 71ms | 0s | 0.000
| |  P99| 454ms| 459ms | 5ms | 1.102
| RoleStore.ChannelHigherScopedPermissions |  Avg| 23ms| 126ms | 103ms | 455.086
| |  P99| 228ms| 988ms | 760ms | 332.606
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 25ms| 26ms | 1ms | 4.004
| |  P99| 239ms| 242ms | 3ms | 1.256
| SessionStore.GetSessionsExpired |  Avg| 80ms| 44ms | -36ms | -45.222
| |  P99| 246ms| 232ms | -14ms | -5.694
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 53ms| 59ms | 6ms | 11.428
| |  P99| 473ms| 632ms | 159ms | 33.580
| SessionStore.Remove |  Avg| 24ms| 18ms | -6ms | -25.432
| |  P99| 219ms| 96ms | -123ms | -56.293
| SessionStore.Save |  Avg| 58ms| 63ms | 5ms | 8.605
| |  P99| 492ms| 499ms | 7ms | 1.423
| SessionStore.UpdateLastActivityAt |  Avg| 21ms| 21ms | 0s | 0.000
| |  P99| 189ms| 196ms | 7ms | 3.695
| StatusStore.Get |  Avg| 32ms| 38ms | 6ms | 18.735
| |  P99| 407ms| 422ms | 15ms | 3.690
| StatusStore.GetByIds |  Avg| 70ms| 80ms | 10ms | 14.239
| |  P99| 525ms| 797ms | 272ms | 51.809
| StatusStore.SaveOrUpdate |  Avg| 109ms| 167ms | 58ms | 53.439
| |  P99| 1.217s| 2.255s | 1.038s | 85.282
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 50ms| 40ms | -10ms | -19.845
| |  P99| 236ms| 235ms | -1ms | -0.424
| StatusStore.UpdateLastActivityAt |  Avg| 25ms| 26ms | 1ms | 3.933
| |  P99| 219ms| 222ms | 3ms | 1.373
| SystemStore.GetByName |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 147ms| 155ms | 8ms | 5.455
| TeamStore.Get |  Avg| 59ms| 65ms | 6ms | 10.096
| |  P99| 585ms| 658ms | 73ms | 12.473
| TeamStore.GetAllPage |  Avg| 50ms| 59ms | 9ms | 17.830
| |  P99| 475ms| 495ms | 20ms | 4.212
| TeamStore.GetByName |  Avg| 56ms| 60ms | 4ms | 7.177
| |  P99| 584ms| 629ms | 45ms | 7.702
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 52ms| 60ms | 8ms | 15.239
| |  P99| 485ms| 499ms | 14ms | 2.890
| TeamStore.GetMany |  Avg| 52ms| 0s | -52ms | -100.682
| |  P99| 99ms| 0s | -99ms | -99.832
| TeamStore.GetMember |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 95ms| 98ms | 3ms | 3.153
| TeamStore.GetTeamsByUserId |  Avg| 53ms| 63ms | 10ms | 18.925
| |  P99| 473ms| 496ms | 23ms | 4.864
| TeamStore.GetTeamsForUser |  Avg| 52ms| 55ms | 3ms | 5.741
| |  P99| 486ms| 480ms | -6ms | -1.236
| TeamStore.SaveMember |  Avg| 133ms| 143ms | 10ms | 7.514
| |  P99| 601ms| 743ms | 142ms | 23.623
| ThreadStore.Get |  Avg| 81ms| 84ms | 3ms | 3.702
| |  P99| 638ms| 665ms | 27ms | 4.235
| ThreadStore.GetMembershipForUser |  Avg| 65ms| 71ms | 6ms | 9.235
| |  P99| 627ms| 668ms | 41ms | 6.544
| ThreadStore.GetTeamsUnreadForUser |  Avg| 77ms| 84ms | 7ms | 9.077
| |  P99| 877ms| 898ms | 21ms | 2.393
| ThreadStore.GetThreadFollowers |  Avg| 66ms| 71ms | 5ms | 7.576
| |  P99| 677ms| 707ms | 30ms | 4.432
| ThreadStore.GetThreadForUser |  Avg| 95ms| 105ms | 10ms | 10.491
| |  P99| 898ms| 932ms | 34ms | 3.786
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 74ms| 84ms | 10ms | 13.494
| |  P99| 720ms| 778ms | 58ms | 8.053
| ThreadStore.GetThreadsForUser |  Avg| 83ms| 92ms | 9ms | 10.787
| |  P99| 775ms| 822ms | 47ms | 6.063
| ThreadStore.GetTotalThreads |  Avg| 53ms| 60ms | 7ms | 13.314
| |  P99| 492ms| 550ms | 58ms | 11.797
| ThreadStore.GetTotalUnreadMentions |  Avg| 53ms| 60ms | 7ms | 13.291
| |  P99| 491ms| 528ms | 37ms | 7.530
| ThreadStore.GetTotalUnreadThreads |  Avg| 54ms| 58ms | 4ms | 7.452
| |  P99| 498ms| 498ms | 0s | 0.000
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 53ms| 60ms | 7ms | 13.106
| |  P99| 488ms| 521ms | 33ms | 6.758
| ThreadStore.MaintainMembership |  Avg| 46ms| 46ms | 0s | 0.000
| |  P99| 329ms| 350ms | 21ms | 6.382
| ThreadStore.MarkAllAsReadByChannels |  Avg| 26ms| 29ms | 3ms | 11.398
| |  P99| 216ms| 224ms | 8ms | 3.708
| ThreadStore.MarkAllAsReadByTeam |  Avg| 25ms| 10ms | -15ms | -61.006
| |  P99| 49ms| 25ms | -24ms | -48.731
| ThreadStore.MarkAsRead |  Avg| 20ms| 21ms | 1ms | 4.936
| |  P99| 163ms| 182ms | 19ms | 11.625
| ThreadStore.UpdateMembership |  Avg| 23ms| 24ms | 1ms | 4.366
| |  P99| 199ms| 204ms | 5ms | 2.518
| TokenStore.Cleanup |  Avg| 20ms| 35ms | 15ms | 74.160
| |  P99| 50ms| 98ms | 48ms | 96.970
| UserAccessTokenStore.GetByToken |  Avg| 59ms| 105ms | 46ms | 78.237
| |  P99| 450ms| 815ms | 365ms | 81.111
| UserStore.AutocompleteUsersInChannel |  Avg| 574ms| 629ms | 55ms | 9.586
| |  P99| 2.294s| 2.357s | 63ms | 2.746
| UserStore.Count |  Avg| 299ms| 301ms | 2ms | 0.668
| |  P99| 985ms| 972ms | -13ms | -1.320
| UserStore.Get |  Avg| 29ms| 30ms | 1ms | 3.434
| |  P99| 398ms| 414ms | 16ms | 4.019
| UserStore.GetAllProfiles |  Avg| 47ms| 55ms | 8ms | 17.066
| |  P99| 473ms| 507ms | 34ms | 7.182
| UserStore.GetAllProfilesInChannel |  Avg| 1.386s| 1.645s | 259ms | 18.692
| |  P99| 4.75s| 4.85s | 100ms | 2.105
| UserStore.GetByUsername |  Avg| 73ms| 99ms | 26ms | 35.699
| |  P99| 547ms| 1.379s | 832ms | 151.963
| UserStore.GetForLogin |  Avg| 42ms| 51ms | 9ms | 21.426
| |  P99| 457ms| 482ms | 25ms | 5.470
| UserStore.GetMany |  Avg| 64ms| 192ms | 128ms | 199.061
| |  P99| 244ms| 4.325s | 4.081s | 1669.122
| UserStore.GetProfileByIds |  Avg| 53ms| 57ms | 4ms | 7.526
| |  P99| 492ms| 558ms | 66ms | 13.420
| UserStore.GetProfilesByUsernames |  Avg| 60ms| 67ms | 7ms | 11.607
| |  P99| 498ms| 579ms | 81ms | 16.268
| UserStore.GetProfilesInChannel |  Avg| 30ms| 79ms | 49ms | 163.346
| |  P99| 99ms| 246ms | 147ms | 148.485
| UserStore.GetUnreadCount |  Avg| 58ms| 64ms | 6ms | 10.341
| |  P99| 583ms| 748ms | 165ms | 28.290
| UserStore.IsEmpty |  Avg| 21ms| 29ms | 8ms | 37.487
| |  P99| 288ms| 392ms | 104ms | 36.155
| UserStore.Save |  Avg| 104ms| 104ms | 0s | 0.000
| |  P99| 471ms| 468ms | -3ms | -0.637
| UserStore.Search |  Avg| 192ms| 210ms | 18ms | 9.378
| |  P99| 1.183s| 1.484s | 301ms | 25.453
| UserStore.Update |  Avg| 47ms| 45ms | -2ms | -4.246
| |  P99| 249ms| 249ms | 0s | 0.000
| UserStore.UpdateFailedPasswordAttempts |  Avg| 16ms| 16ms | 0s | 0.000
| |  P99| 176ms| 191ms | 15ms | 8.505
| UserStore.UpdateUpdateAt |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 111ms| 118ms | 7ms | 6.332
| UserTermsOfServiceStore.GetByUser |  Avg| 51ms| 60ms | 9ms | 17.576
| |  P99| 473ms| 496ms | 23ms | 4.858
| WebhookStore.GetOutgoingByTeam |  Avg| 74ms| 81ms | 7ms | 9.403
| |  P99| 691ms| 737ms | 46ms | 6.660
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 1.456s| 1.58s | 124ms | 8.518
| | P99| 4.997s| 7.764s | 2.767s | 55.377
| addTeamMember | Avg| 2.882s| 3.374s | 492ms | 17.070
| | P99| 10s| 10s | 0s | 0.000
| autocompleteChannelsForTeamForSearch | Avg| 443ms| 479ms | 36ms | 8.123
| | P99| 2.466s| 3.026s | 560ms | 22.708
| autocompleteUsers | Avg| 465ms| 505ms | 40ms | 8.598
| | P99| 2.268s| 2.327s | 59ms | 2.602
| createCategoryForTeamForUser | Avg| 183ms| 295ms | 112ms | 61.105
| | P99| 965ms| 980ms | 15ms | 1.554
| createChannel | Avg| 148ms| 171ms | 23ms | 15.568
| | P99| 491ms| 489ms | -2ms | -0.407
| createDirectChannel | Avg| 1.022s| 1.027s | 5ms | 0.489
| | P99| 4.493s| 4.639s | 146ms | 3.249
| createGroupChannel | Avg| 1.81s| 1.835s | 25ms | 1.381
| | P99| 8.25s| 6.475s | -1.775s | -21.515
| createPost | Avg| 3.8s| 4.042s | 242ms | 6.369
| | P99| 10s| 10s | 0s | 0.000
| createUser | Avg| 227ms| 252ms | 25ms | 10.990
| | P99| 1.443s| 1.814s | 371ms | 25.705
| deletePost | Avg| 359ms| 447ms | 88ms | 24.482
| | P99| 2.335s| 4.6s | 2.265s | 97.002
| followThreadByUser | Avg| 180ms| 257ms | 77ms | 42.687
| | P99| 493ms| 2.02s | 1.527s | 309.789
| getAllTeams | Avg| 53ms| 61ms | 8ms | 15.168
| | P99| 482ms| 498ms | 16ms | 3.319
| getCategoriesForTeamForUser | Avg| 125ms| 139ms | 14ms | 11.234
| | P99| 1.149s| 1.18s | 31ms | 2.698
| getChannel | Avg| 134ms| 130ms | -4ms | -2.977
| | P99| 1.364s| 950ms | -414ms | -30.357
| getChannelMember | Avg| 79ms| 83ms | 4ms | 5.073
| | P99| 680ms| 720ms | 40ms | 5.881
| getChannelMembers | Avg| 46ms| 147ms | 101ms | 221.532
| | P99| 239ms| 492ms | 253ms | 105.637
| getChannelMembersForTeamForUser | Avg| 70ms| 78ms | 8ms | 11.390
| | P99| 661ms| 739ms | 78ms | 11.800
| getChannelStats | Avg| 104ms| 128ms | 24ms | 23.030
| | P99| 1.452s| 1.825s | 373ms | 25.683
| getChannelUnread | Avg| 108ms| 103ms | -5ms | -4.621
| | P99| 902ms| 859ms | -43ms | -4.767
| getChannelsForTeamForUser | Avg| 78ms| 85ms | 7ms | 9.024
| | P99| 727ms| 767ms | 40ms | 5.504
| getChannelsForUser | Avg| 87ms| 90ms | 3ms | 3.445
| | P99| 785ms| 737ms | -48ms | -6.117
| getClientConfig | Avg| 33ms| 33ms | 0s | 0.000
| | P99| 352ms| 375ms | 23ms | 6.537
| getFilePreview | Avg| 174ms| 180ms | 6ms | 3.456
| | P99| 979ms| 988ms | 9ms | 0.920
| getFileThumbnail | Avg| 163ms| 172ms | 9ms | 5.513
| | P99| 979ms| 991ms | 12ms | 1.226
| getPostThread | Avg| 416ms| 450ms | 34ms | 8.172
| | P99| 2.491s| 3.023s | 532ms | 21.361
| getPostsForChannel | Avg| 859ms| 946ms | 87ms | 10.126
| | P99| 9.116s| 9.43s | 314ms | 3.444
| getPostsForChannelAroundLastUnread | Avg| 243ms| 276ms | 33ms | 13.595
| | P99| 2.322s| 2.366s | 44ms | 1.895
| getPreferences | Avg| 59ms| 68ms | 9ms | 15.259
| | P99| 493ms| 574ms | 81ms | 16.415
| getProfileImage | Avg| 108ms| 100ms | -8ms | -7.389
| | P99| 499ms| 495ms | -4ms | -0.801
| getPublicChannelsForTeam | Avg| 89ms| 111ms | 22ms | 24.816
| | P99| 693ms| 810ms | 117ms | 16.883
| getTeamMember | Avg| 31ms| 27ms | -4ms | -12.985
| | P99| 242ms| 236ms | -6ms | -2.482
| getTeamMembersForUser | Avg| 55ms| 58ms | 3ms | 5.440
| | P99| 491ms| 487ms | -4ms | -0.814
| getTeamsForUser | Avg| 53ms| 63ms | 10ms | 18.825
| | P99| 474ms| 497ms | 23ms | 4.855
| getTeamsUnreadForUser | Avg| 91ms| 102ms | 11ms | 12.100
| | P99| 943ms| 966ms | 23ms | 2.438
| getThreadsForUser | Avg| 87ms| 95ms | 8ms | 9.248
| | P99| 850ms| 891ms | 41ms | 4.826
| getUser | Avg| 71ms| 81ms | 10ms | 14.127
| | P99| 605ms| 761ms | 156ms | 25.779
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 4ms| 4ms | 0s | 0.000
| | P99| 90ms| 88ms | -2ms | -2.218
| getUsers | Avg| 64ms| 72ms | 8ms | 12.405
| | P99| 610ms| 747ms | 137ms | 22.471
| getUsersByIds | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 198ms| 211ms | 13ms | 6.572
| getUsersByNames | Avg| 62ms| 68ms | 6ms | 9.747
| | P99| 515ms| 606ms | 91ms | 17.658
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 301ms| 321ms | 20ms | 6.640
| | P99| 2.371s| 2.395s | 24ms | 1.012
| logout | Avg| 346ms| 322ms | -24ms | -6.933
| | P99| 1.87s| 1.945s | 75ms | 4.011
| patchPost | Avg| 1.474s| 6.638s | 5.164s | 350.402
| | P99| 4.062s| 10s | 5.938s | 146.166
| removeUserCustomStatus | Avg| 527ms| 500ms | -27ms | -5.128
| | P99| 2.357s| 2.383s | 26ms | 1.103
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 288ms| 316ms | 28ms | 9.731
| | P99| 2.143s| 2.238s | 95ms | 4.433
| searchAllChannels | Avg| 365ms| 408ms | 43ms | 11.795
| | P99| 6.931s| 7.723s | 792ms | 11.427
| searchGroupChannels | Avg| 84ms| 99ms | 15ms | 17.847
| | P99| 744ms| 871ms | 127ms | 17.067
| searchPostsInTeam | Avg| 383ms| 390ms | 7ms | 1.826
| | P99| 4.729s| 4.624s | -105ms | -2.221
| searchUsers | Avg| 195ms| 214ms | 19ms | 9.722
| | P99| 1.234s| 1.531s | 297ms | 24.064
| setPostReminder | Avg| 364ms| 265ms | -99ms | -27.188
| | P99| 4.275s| 2.095s | -2.18s | -50.994
| unfollowThreadByUser | Avg| 268ms| 235ms | -33ms | -12.312
| | P99| 1.555s| 1.248s | -307ms | -19.742
| updateCategoriesForTeamForUser | Avg| 738ms| 585ms | -153ms | -20.720
| | P99| 2.447s| 2.393s | -54ms | -2.207
| updatePreferences | Avg| 84ms| 92ms | 8ms | 9.540
| | P99| 470ms| 476ms | 6ms | 1.277
| updateReadStateAllThreadsByUser | Avg| 25ms| 10ms | -15ms | -60.696
| | P99| 49ms| 25ms | -24ms | -48.731
| updateReadStateThreadByUser | Avg| 588ms| 644ms | 56ms | 9.521
| | P99| 3.669s| 4.064s | 395ms | 10.767
| updateUserCustomStatus | Avg| 646ms| 612ms | -34ms | -5.260
| | P99| 2.463s| 2.415s | -48ms | -1.949
| uploadFileStream | Avg| 598ms| 578ms | -20ms | -3.346
| | P99| 2.399s| 2.375s | -24ms | -1.000
| viewChannel | Avg| 192ms| 208ms | 16ms | 8.324
| | P99| 1.563s| 1.728s | 165ms | 10.555
